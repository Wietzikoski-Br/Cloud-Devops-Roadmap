#Resumo da Aula de Cabeamento estruturado#:

1. Camadas Física e de Enlace (Modelo OSI)

A aula começa revisando duas camadas importantes do modelo OSI:

Camada Física

Responsável pela transmissão dos bits (0 e 1) pelo meio de comunicação.

O objetivo é garantir que o bit enviado chegue corretamente ao destino.

Os sinais podem ser transmitidos por:

Impulsos elétricos (cabos de cobre)

Ondas eletromagnéticas (wireless)

Sinais de luz (fibra óptica)

Modos de comunicação

Simplex: comunicação em um único sentido.

Half-duplex: comunicação nos dois sentidos, mas não ao mesmo tempo.

Full-duplex: comunicação nos dois sentidos simultaneamente.

Tipos de comutação

Comutação de circuitos (ex.: telefonia tradicional)

Comutação de pacotes (ex.: internet)

Camada de Enlace

Organiza os bits em quadros (frames).

Faz detecção e correção de erros de transmissão.

Garante que os dados sejam enviados corretamente pela rede.
--------------------------------------------------------------------------------------------------
2. Padrão Ethernet

Para permitir que equipamentos de diferentes fabricantes se comuniquem, foram criados padrões de rede, sendo o principal o Ethernet (IEEE 802.3).

Principais velocidades do Ethernet

Ethernet – 10 Mbps

Fast Ethernet – 100 Mbps

Gigabit Ethernet – 1 Gbps

10 Gigabit Ethernet – 10 Gbps

100 Gigabit Ethernet – 100 Gbps

Terabit Ethernet – até 1 Tbps

Exemplos de tecnologias

Ethernet (10 Mbps)

Cabo: UTP CAT3

Conector: RJ-45

Alcance: 100 m (cobre) ou até 2 km (fibra)

Fast Ethernet (100 Mbps)

Cabo: UTP CAT5

Alcance: 100 m

Gigabit Ethernet (1 Gbps)

Cabo: CAT5e ou CAT6

Alcance: 100 m

Gigabit e 10 Gigabit com fibra

Utilizam fibra óptica

Alcance pode chegar a 40 km dependendo do tipo.

Terabit Ethernet

Usado principalmente em data centers e computação em nuvem.
--------------------------------------------------------------------------------------------------
3. Cabeamento Estruturado

É um sistema organizado de cabos, conectores e equipamentos de rede, seguindo normas técnicas para garantir funcionamento eficiente.

Vantagens

Melhor performance da rede

Maior tempo de funcionamento (uptime)

Manutenção mais fácil

Facilidade de expansão
--------------------------------------------------------------------------------------------------
4. Elementos do Cabeamento Estruturado

Inclui a organização de:

Racks

Patch panels

Switches (camada 2) e roteadores (camada 3)

Servidores

Caminhos e passagens de cabos

Tomadas de rede

Sala de equipamentos / telecomunicações

Tipos de cabeamento

Cabeamento vertical (backbone)
Liga diferentes andares ou prédios.

Cabeamento horizontal
Liga o rack até as tomadas de rede dos usuários.
--------------------------------------------------------------------------------------------------
5. Infraestruturas associadas

Uma rede estruturada também envolve outros sistemas do prédio:

Energia elétrica

Telefonia

Rede de dados

Climatização

Iluminação

Segurança

Também pode alimentar dispositivos via PoE (Power over Ethernet), como:

Telefones VoIP

Câmeras de segurança (CFTV)

Sensores

Alarmes

Sistemas de automação
--------------------------------------------------------------------------------------------------
6. Questões legais

O Código de Defesa do Consumidor (Lei nº 8.078/1990) determina que produtos e serviços devem seguir normas técnicas oficiais, como as definidas pela ABNT.
Ou seja, sistemas de cabeamento devem respeitar padrões técnicos.
--------------------------------------------------------------------------------------------------
7. Conclusão da aula

É fundamental entender as camadas inferiores do modelo OSI.

O Ethernet possui várias velocidades e tecnologias.

O cabeamento estruturado deve seguir normas e ser bem planejado para garantir desempenho e confiabilidade da rede.
--------------------------------------------------------------------------------------------------
#Atividade Pós aula de Cabeamento estruturado#

Questão 1

A camada Física trata dos meios físicos de transmissão dentro de uma rede, que pode ter três modos de transmissão: Em branco 1 Questão 1
Simplex
 , onde existe apenas um sentido para a comunicação. Em branco 2 Questão 1
Full-duplex
 , onde é possível a transferência em ambos os sentidos e ao mesmo tempo e Em branco 3 Questão 1
Half-duplex
  onde existem dois sentidos, porém cada um transmite de cada vez.

A resposta correta é:
A camada Física trata dos meios físicos de transmissão dentro de uma rede, que pode ter três modos de transmissão: [Simplex], onde existe apenas um sentido para a comunicação. [Full‑duplex], onde é possível a transferência em ambos os sentidos e ao mesmo tempo e [Half‑duplex] onde existem dois sentidos, porém cada um transmite de cada vez.
--------------------------------------------------------------------------------------------------
Questão 2

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
Questão 3

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
Questão 4

Em redes, comutar é o ato de encaminhar algum dado a um destinatário. A comutação por circuitos cria um caminho dedicado apenas àquela comunicação, que será utilizado durante toda a transmissão. Já na comutação por pacotes, não há um único caminho, os dados serão transformados em pacotes e daí serão enviados por diferentes caminhos até chegarem ao seu destinatário. Onde são usados cada um dos dois tipos de comutação?

A comutação por pacotes é usada na Internet

A comutação por pacotes é usada nas redes de telefonia analógica

A comutação por circuitos é usada dentro das LANs

A comutação por circuitos é usada na Internet

A resposta correta é:
A comutação por pacotes é usada na Internet
--------------------------------------------------------------------------------------------------
Questão 5

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
Questão 6

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