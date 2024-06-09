# ADA SANTANDER - Curso Digital
# Módulo 02 - Redes e Sistemas

## 01 - O que são redes?
Rede é a conexão entre 2 ou mais dispositivos que trocam informações por meio de uma linguagem pré-estabelecida chamada de protocolo.
### História
#### Início
Darpa, Arpanet.

## 02 - Infraestrutura de redes e os principais equipamentos
### NIC = Network Interface Card
Placa de rede, é o dispositivo responsável por mermitir a conexão do computador com o cabo de rede Ethernet ou por receber ondas de rádio frequência das conexões Wireless.
### Hub
Conextar vários dispositivos. Problema: Não consegue realizar conexões ponto a ponto.
### Switch
Conextar vários dispositivos. Problema: Consegue realizar conexões ponto a ponto.
### Roteador
Procura melhor rota na internet para entregar os pacotes do remetente ao destinatário no menor tempo possível.
### Modem
É o equipamento responsável pela modulação e demodulação do sinal de internet.

## 03 - Cabeamento Estruturado
Padrões estabelecidos que definem como serão organizados os cabos e seus periféricos.
### Normas
* NBR 14.565
* ANSI/TIA 568
* ANSI/TIA 569
### Cabo de Par Trançado
#### UTP
Dividido em 8 fios de cobre intertrançados.
#### STP
Semelhante ao UTP opirém os pares trançados são isolados.
### Cabo Coaxial
Fio Central, condutor do puslo elétrico, tubo de silicone, malha metálica realizando isolamento e uma blindagem plástica.
### Fibra Óptica
A fibra Optica é a tecnologia guiada por cabo que oferece a maior velocidade de transmissão de dados chegando a altas velocidades na casa dos Gbps. A fibra é composta por pedaçõs de vidros que permitem a propagação dos raios de luz que são convertidos por conversores nas extremidades das fibras.
### Hack
Armário que armazena os dispositivos.

## 04 - Modelo OSI e TCP/IP
### Modelo OSI
---
#### Camadas mais próximas do usuário
* 7 Aplicação (protocolo USSH, protocolo DNS)
* 6 Apresentação (cryptography)
* 5 Sessão (sessão de comunicação com o destino)
---
#### Começa a parte de interface de Hardware
* 4 Transporte (protocolo TCP ou UDP)
---
* 3 Rede (roteadores)
---
#### Hardware
* 2 Enlace (comunicação via switch, MAC Adress)
* 1 Física (Protocolo Ethernet. Cabo, switch, modem etc.)
---

### Modelo TCP/IP
---
#### Camadas mais próximas do usuário
* 4 Aplicação
---
#### Começa a parte de interface de Hardware
* 3 Transporte (Protocolo TCP)
---
* 2 Internet (Protocolo IP)
---
#### Hardware
* 1 Acesso a Rede
---

### TCP
Existe uma verificação de chegada de dado.
### UDP
Não existe uma verificação de chegada de dados.
* Característico de Streaming devido à alta velocidade.

## 05 - IPV4 e IPV6
### IP - Internet Protocol
#### IPV4
- 000.000.000.000
- 32 Bits combinados em 4 bytes (octetos de 8 bits)
- 0 a 255 . 0 a 255 . 0 a 255 . 0 a 255
##### NAT
- A rede privada sai do modem utilizando o mesmo IP Publico.

#### IPV6
- 0000.0000.0000.0000.0000.0000.0000.0000
- 128 bits divdidos em 16 pares de bits.

## 06 - Cálculo de sub rede
Cada departamento de uma empresa utiliza uma sub rede e elas se comunicam por uma rota estabelecida.
* Classe A 1-127
  * MASCARA: CHHH 
* Classe B 128-191
  * MASCARA: CCHH
* Classe C 192-223
  * MASCARA: CCCH
* Classe D 224-239 Multicast
* Classe E 240-255 Experimental

### Site para Calculos
https://www.site24x7.com/

## 07 - Domínios, DNS e latência

## 08 - Principais comandos de configuração

## 09 - Segurança

## 10 - Wireless
