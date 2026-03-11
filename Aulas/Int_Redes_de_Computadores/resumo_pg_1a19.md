# Resumo da Aula: Introdução às Redes de Computadores Paginas 1 a 19

## 1. Conceito de Rede
- **Rede**: conjunto de elementos interligados que cooperam entre si.
- **Rede de computadores**: interconexão de dispositivos para troca de dados e compartilhamento de recursos (hardware e software).
- Importância dos **protocolos** e padrões para garantir que os computadores “falem a mesma língua”.

---

## 2. Vantagens das Redes
- **Comunicação**: mensagens instantâneas, e-mails, voz e vídeo em tempo real.
- **Conectividade**: integração entre LANs e WANs.
- **Compartilhamento de dados**: arquivos, bancos de dados e repositórios de código.
- **Compartilhamento de recursos físicos**: impressoras, servidores, dispositivos.
- **Acesso à Internet**: conexão à maior rede mundial.
- **Compartilhamento do acesso à Internet**: múltiplos dispositivos usando um único link.
- **Balanceamento de carga**: otimização e redundância de serviços.
- **Entretenimento**: jogos online, streaming (Netflix, Spotify).

---

## 3. Desafios das Redes
- **Custo de hardware e software**: investimento elevado em grandes redes.
- **Administração**: necessidade de monitoramento e profissionais especializados.
- **Compartilhamento indesejado**: vírus, malware, spam.
- **Atividades ilegais**: ataques cibernéticos, roubo de dados, crimes digitais.
- **Privacidade e nuvem**: dados armazenados em servidores remotos sem controle direto do usuário.

---

## 4. Dispositivos de Rede

### 4.1 Dispositivos Finais
- Computadores, servidores, impressoras, telefones IP.
- Smart TVs, tablets, smartphones, câmeras de vigilância.
- Possuem **endereço físico (MAC)** e **endereço lógico (IP)**.

### 4.2 Dispositivos Intermediários
- Conectam dispositivos finais e diferentes redes.
- Funções:
  - Regenerar e retransmitir dados.
  - Manter tabelas de rotas.
  - Redirecionar tráfego em caso de falha.
  - Aplicar políticas de segurança.

### 4.3 Roteadores
- Encaminham **pacotes** entre redes.
- Funções:
  - Default Gateway.
  - Servidor ou agente DHCP.
  - Tabelas de rotas internas e externas.
  - Protocolos de roteamento (ex.: OSPF).
  - Filtragem de pacotes.
- Exemplo: Cisco 1941 (Packet Tracer).

### 4.4 Switches
- Conectam dispositivos finais usando **endereços MAC**.
- Tipos:
  - **Não-gerenciáveis**: simples, domésticos (ex.: D-LINK DGS-1008A).
  - **Gerenciáveis**: configuráveis via IP/SSH, usados em VLANs.
  - **Camada 3 (multicamada)**: fazem roteamento inter-VLAN.
- Exemplo: Cisco Catalyst 2960 (camada 2), Cisco Catalyst 3650 (camada 3).

### 4.5 Hubs
- Dispositivo obsoleto, atua na **camada física**.
- Repete sinais em **broadcast** para todas as portas.
- Opera em **half-duplex**.
- Usado até os anos 1990 em redes Ethernet.

### 4.6 Outros Dispositivos
- Bridges (precursor dos switches).
- Firewalls (hardware).
- IDS (Intrusion Detection System).
- Repetidores sem fio.

---

## 5. Conclusão
- Redes de computadores são essenciais para comunicação, compartilhamento e conectividade global.
- Dispositivos finais e intermediários têm papéis distintos e complementares.
- O entendimento técnico de roteadores, switches e hubs é fundamental para projetar e administrar redes modernas.
