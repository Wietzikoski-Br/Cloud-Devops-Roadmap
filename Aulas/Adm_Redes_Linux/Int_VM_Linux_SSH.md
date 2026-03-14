# 📘 Resumo da Aula/Laboratório: Instalação do Ubuntu, Virtualização e Conexão SSH

## 🎯 Objetivo
- Instalar e configurar o **Ubuntu Desktop 20.04.6 LTS** em ambiente virtualizado no **Oracle VirtualBox**.  
- Configurar **redirecionamento de portas** para permitir acesso remoto via **SSH**.  
- Estabelecer conexão entre **Windows (PowerShell)** e **Linux (VM)**.  
- Validar a comunicação com a instalação e execução do **Neofetch**.  

---

## ✅ Atividades Realizadas
1. **Instalação do Ubuntu em VM** no VirtualBox.  
2. **Configuração de rede NAT e rede interna** na VM.  
3. **Instalação do servidor SSH no Ubuntu**:
   ```bash
   sudo apt update
   sudo apt install openssh-server -y
   sudo systemctl enable ssh
   sudo systemctl start ssh
   sudo systemctl status ssh
## Configuração do redirecionamento de portas no VirtualBox:

**Acesse: Configurações da VM → Rede → Avançado → Redirecionamento de Portas.**

Adicione uma regra:
   ```bash
   Nome: SSH

   Protocolo: TCP

   IP Hospedeiro: 127.0.0.1

   Porta Hospedeiro: 2222

   IP Convidado: 10.0.2.15

   Porta Convidado: 22
   ```
## Conexão via PowerShell no Windows:
   ```bash
   ssh username@127.0.0.1 -p 2222
```
## Instalação e execução do Neofetch para validar a conexão:
   ```bash
   sudo apt install neofetch -y
   neofetch
```
# 📚 Conceitos Aplicados
Virtualização com Oracle VirtualBox: Criação de ambientes isolados para estudo sem afetar o sistema hospedeiro.

NAT e Redirecionamento de Portas: Permite que a VM acesse a internet e seja acessada pelo hospedeiro via mapeamento de portas.

SSH (Secure Shell): Protocolo seguro para administração remota de sistemas Linux.

Endereçamento IP:

127.0.0.1 (localhost): IP de loopback do hospedeiro.

10.0.2.15: IP atribuído à VM pelo VirtualBox em modo NAT.

Neofetch: Ferramenta para exibir informações do sistema, útil para validar a instalação e conexão.

# 🎯 Resultado
Ubuntu instalado e operacional em VM.

SSH configurado e funcional com redirecionamento de portas.

Conexão estabelecida entre Windows PowerShell e Ubuntu VM.

Execução do Neofetch confirmando a comunicação e funcionamento do ambiente.

# 🔎 Conclusão
A prática consolidou o entendimento de virtualização, configuração de rede e acesso remoto via SSH.

O uso de 127.0.0.1 e 10.0.2.15 demonstrou a importância da correta configuração de IPs e portas para comunicação entre hospedeiro e convidado.

Próximos passos: aprofundar em serviços de rede (DNS, DHCP, Web) e explorar automação de conexões SSH com scripts.