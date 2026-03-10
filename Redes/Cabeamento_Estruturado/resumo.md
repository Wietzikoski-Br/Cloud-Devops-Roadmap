# Resumo da Aula: Cabeamento Estruturado

## 1. Camadas Física e de Enlace (Modelo OSI)
- **Camada Física**
  - Transmissão de bits (0 e 1) pelo meio físico.
  - Meios: impulsos elétricos (cobre), ondas eletromagnéticas (wireless), sinais de luz (fibra óptica).
  - Modos de comunicação:
    - Simplex → um único sentido.
    - Half-duplex → dois sentidos, mas alternados.
    - Full-duplex → dois sentidos simultâneos.
  - Tipos de comutação:
    - Circuitos → telefonia tradicional.
    - Pacotes → internet.

- **Camada de Enlace**
  - Organiza bits em quadros (frames).
  - Detecção e correção de erros.
  - Garante envio correto dos dados.

---

## 2. Padrão Ethernet (IEEE 802.3)
- **Velocidades principais:**
  - Ethernet → 10 Mbps
  - Fast Ethernet → 100 Mbps
  - Gigabit Ethernet → 1 Gbps
  - 10 Gigabit → 10 Gbps
  - 100 Gigabit → 100 Gbps
  - Terabit → até 1 Tbps

- **Exemplos de tecnologias:**
  - Ethernet (10 Mbps) → UTP CAT3, RJ-45, alcance 100m.
  - Fast Ethernet (100 Mbps) → UTP CAT5, alcance 100m.
  - Gigabit Ethernet (1 Gbps) → CAT5e/CAT6, alcance 100m.
  - Fibra óptica → até 40 km.
  - Terabit Ethernet → data centers e nuvem.

---

## 3. Cabeamento Estruturado
- Sistema organizado de cabos, conectores e equipamentos.
- **Vantagens:**
  - Melhor performance.
  - Maior uptime.
  - Manutenção facilitada.
  - Facilidade de expansão.

---

## 4. Elementos do Cabeamento Estruturado
- Racks, patch panels, switches, roteadores, servidores.
- Caminhos e passagens de cabos.
- Tomadas de rede e sala de telecom.
- **Tipos:**
  - Vertical (backbone).
  - Horizontal (rack → usuários).

---

## 5. Infraestruturas Associadas
- Energia elétrica, telefonia, rede de dados, climatização, iluminação, segurança.
- **PoE (Power over Ethernet):**
  - Alimenta dispositivos como VoIP, câmeras CFTV, sensores, alarmes.

---

## 6. Questões Legais
- Código de Defesa do Consumidor (Lei nº 8.078/1990).
- Normas técnicas da ABNT devem ser seguidas.

---

## 7. Conclusão
- Importância das camadas inferiores do OSI.
- Ethernet com várias velocidades e tecnologias.
- Cabeamento estruturado garante desempenho e confiabilidade.

---
# Atividade Pós aula de Cabeamento estruturado#

### Questão 1

A camada Física trata dos meios físicos de transmissão dentro de uma rede, que pode ter três modos de transmissão: ---, onde existe apenas um sentido para a comunicação. ---, onde é possível a transferência em ambos os sentidos e ao mesmo tempo e --- onde existem dois sentidos, porém cada um transmite de cada vez.

A resposta correta é:
A camada Física trata dos meios físicos de transmissão dentro de uma rede, que pode ter três modos de transmissão: [Simplex], onde existe apenas um sentido para a comunicação. [Full‑duplex], onde é possível a transferência em ambos os sentidos e ao mesmo tempo e [Half‑duplex] onde existem dois sentidos, porém cada um transmite de cada vez.
--------------------------------------------------------------------------------------------------
### Questão 2

No modelo OSI a camada física é responsável pela transmissão dos bits por um meio de comunicação. A rede deve garantir que, quando o emissor enviar um bit de valor 1, o receptor receberá o mesmo bit com o valor de 1, ou seja, não pode haver uma troca do valor de 1 para 0. 
Qual destes não é um meio de transmissão da camada Física?

a.
Fibra óptica

b.
MAC address

c.
Cabo de cobre

d.
Ondas eletromagnéticas 

A resposta correta é:
MAC address
--------------------------------------------------------------------------------------------------
### Questão 3

Escolha a alternativa que completa  os "✍️" da frase abaixo, baseado nas informações discutidas na videoaula:
O Cabeamento Estruturado tem como objetivo organizar os ✍️ seguindo  ✍️  e uma de suas vantagens é a  ✍️  de expansão da rede.

a.
"meios de transmissão", "normas vigentes", "facilidade"

b.
"racks", "as regras da empresa", "velocidade"

c.
"cabos", " código de defesa do consumidor", "estabilidade"

d.
"cabos", "patch panel", "dificuldade"

A resposta correta é: "meios de transmissão", "normas vigentes", "facilidade"
--------------------------------------------------------------------------------------------------
### Questão 4

Em redes, comutar é o ato de encaminhar algum dado a um destinatário. A comutação por circuitos cria um caminho dedicado apenas àquela comunicação, que será utilizado durante toda a transmissão. Já na comutação por pacotes, não há um único caminho, os dados serão transformados em pacotes e daí serão enviados por diferentes caminhos até chegarem ao seu destinatário. Onde são usados cada um dos dois tipos de comutação?

A comutação por pacotes é usada na Internet

A comutação por pacotes é usada nas redes de telefonia analógica

A comutação por circuitos é usada dentro das LANs

A comutação por circuitos é usada na Internet

A resposta correta é:
A comutação por pacotes é usada na Internet
--------------------------------------------------------------------------------------------------
### Questão 5

Qual tecnologia permite, em interfaces Ethernet, que o cabo UTP (cabo de rede convencional) possa, além de transmitir dados, alimentar eletricamente os dispositivos de rede, quando há suporte?
Questão 5Resposta

a.
Gigabit Ethernet

b.
EoE - Energy over Ethernet

c.
PoE - Power Over Ethernet

d.
Não é possível que um cabo UTP faça isso

A resposta correta é:
PoE - Power Over Ethernet
--------------------------------------------------------------------------------------------------
### Questão 6

É correto afirmar que as notações 2Gbps, 3Kbps  podem ser corretamente descritas, respectivamente, como:

Questão 6Resposta

a.
20.000.000 bits por segundo e 300 bits por segundo 

b.
2.000.000 bits por segundo e 3 bits por segundo

c.
2.000.000.000.000 bits por segundo e 3.000.000 bits por segundo 

d.
2.000.000.000 bits por segundo e 3.000 bits por segundo 

A resposta correta é:
2.000.000.000 bits por segundo e 3.000 bits por segundo
--------------------------------------------------------------------------------------------------