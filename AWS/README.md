# 🚀 Primeira Instância Ubuntu na AWS

## 🎯 Objetivo
Configurar uma **VPC básica na AWS**, criar subnets, rotas e lançar a primeira instância **Ubuntu EC2**, conectando via SSH para validar o funcionamento da rede.  

---

## ✅ Resumo do que foi realizado
- Criada a **VPC-Estudo** com bloco CIDR `xxx.xxx.xxx.xxx/xx`.  
- Configuradas **subnet pública (xxx.xxx.xxx.xxx/xx)** e **subnet privada (xxx.xxx.xxx.xxx/xx)**.  
- Criado e associado um **Internet Gateway (IGW-Estudo)** à VPC.  
- Configurada **Route Table Pública** com rota `0.0.0.0/0 → IGW`.  
- Associada a **Route Table Pública** à subnet pública.  
- Criada **instância EC2 Ubuntu 24.04 LTS** na subnet pública.  
- Configurado **par de chaves SSH (ubuntu-key.pem)** para acesso seguro.  
- Conectado com sucesso via SSH à instância.  
- Executado o primeiro comando de manutenção:  
  ```bash
  sudo apt update && sudo apt upgrade -y
---
  ## 🔹 Passo a Passo Detalhado
## 1. Criar a VPC
Nome: VPC-Estudo

Bloco CIDR IPv4: xxx.xxx.xxx.xxx/xx

Sem IPv6, locação padrão.

![](<Captura de tela 2026-03-13 002705-1.png>)
--
![](<Captura de tela 2026-03-13 002756.png>)
--
![](<Captura de tela 2026-03-13 003859-1.png>)
--
![](<Captura de tela 2026-03-13 004536-1.png>)
--
## 2. Criar Subnets
Subnet Pública: xxx.xxx.xxx.xxx/xx

Subnet Privada: xxx.xxx.xxx.xxx/xx

![](<Captura de tela 2026-03-13 004551.png>)
--
![](<Captura de tela 2026-03-13 004724-1.png>)
--
![](<Captura de tela 2026-03-13 004815-1.png>)
## 3. Criar Internet Gateway
Nome: IGW-Estudo

Associado à VPC VPC-Estudo.

![](<Captura de tela 2026-03-13 005455-1.png>)
--
![](<Captura de tela 2026-03-13 005550-1.png>)
--
4. Configurar Route Tables
Route Table Pública:

xxx.xxx.xxx.xxx/xx → local

0.0.0.0/0 → IGW-Estudo

Associada à Subnet Pública.

Route Table Privada: apenas rota local.

![](<Captura de tela 2026-03-13 005644-1.png>)
--
![](<Captura de tela 2026-03-13 005720-1.png>)
--
![](<Captura de tela 2026-03-13 010445-1.png>)
--
## 5. Criar Instância EC2 Ubuntu
AMI: Ubuntu Server 24.04 LTS

Tipo: t3.micro (nível gratuito).

Par de chaves: ubuntu-key.pem.

Subnet: Pública (com IP público habilitado).

Grupo de segurança:

SSH (22) → 0.0.0.0/0

HTTP (80) → 0.0.0.0/0

HTTPS (443) → 0.0.0.0/0

![](<Captura de tela 2026-03-13 010729.png>)
--
![](<Captura de tela 2026-03-13 011922-1.png>)
--
![](<Captura de tela 2026-03-13 012014-1.png>)
--
![](<Captura de tela 2026-03-13 012528-1.png>)
--
![](<Captura de tela 2026-03-13 012656-1.png>)
--
## 6. Conectar via SSH
bash
ssh -i "ubuntu-key.pem" ubuntu@<Elastic-IP>
## 7. Atualizar Sistema
bash
sudo apt update && sudo apt upgrade -y

![](<Captura de tela 2026-03-13 013514-1.png>)
--
## 🎯 Resultado
Infraestrutura mínima em nuvem criada com sucesso.

Instância Ubuntu acessível via SSH.

Conceitos de roteador, switch multicamadas e dispositivos finais aplicados na prática.