- **Classes de endereço IP**

+ **Classe A**: 0.0.0.0 a 127.255
255.255 (128 redes com 16.777.216 hosts cada)
+ **Classe B**: 128.0.0.0 a 191.255.
255.255 (16.384 redes com 65.536 hosts cada)
+ **Classe C**: 192.0.0.0 a 223.255.
255.255 (2.097.152 redes com 256 hosts cada)
+ **Classe D**: 224.0.0.0 a 239.255.
255.255 (endereços multicast)
+ **Classe E**: 240.0.0.0 a 254.255.
255.255 (endereços reservados)
- **Máscara de sub-rede**
+ **Máscara de sub-rede**: é um valor que define a divisão entre
a parte de rede e a parte de host em um endereço IP.
+ **Exemplo**: 255.255.255.0 (24 bits de rede e
8 bits de host)
- **Sub-rede**
+ **Sub-rede**: é uma divisão de uma rede maior em
menores redes, utilizando uma máscara de sub-rede.
+ **Exemplo**: uma rede classe C (192.168.1.0/24)
pode ser dividida em 4 sub-redes (192.168.1.0/
26, 192.168.1.64/26, 192.168.1.
128/26 e 192.168.1.192/26)
- **VLSM (Variable Length Subnet Masking)**
+ **VLSM**: é uma técnica de sub-rede que permite
utilizar máscaras de sub-rede diferentes em
uma mesma rede.
- **CIDR (Classless Inter-Domain Routing)**
+ **CIDR**: é uma técnica de roteamento que
permite agrupar redes contíguas em uma
única rota, utilizando uma máscara de
sub-rede.
- **Private IP Address**
+ **Private IP Address**: são endereços IP
reservados para uso em redes privadas,
não sendo roteáveis na internet.
+ **Exemplos**: 10.0.0.0/8, 172.
16.0.0/12, 192.168.0.0/16
- **NAT (Network Address Translation)**
+ **NAT**: é uma técnica que permite
conectar uma rede privada à internet,
utilizando um endereço IP público.
- **DHCP (Dynamic Host Configuration Protocol)**
+ **DHCP**: é um protocolo que permite
atribuir endereços IP dinamicamente
aos dispositivos em uma rede.
- **IPV6 (Internet Protocol Version 6)**
+ **IPV6**: é a próxima geração do protocolo
IP, com endereços de 128 bits.
+ **Exemplo**: 2001:0db8:85a3:0000:
0000:8a2e:0370:7334
- **Tunneling**
+ **Tunneling**: é uma técnica que permite
encapsular pacotes de uma rede em
pacotes de outra rede, permitindo
a comunicação entre redes com
protocolos diferentes.
- **Proxy ARP (Address Resolution Protocol)**
+ **Proxy ARP**: é uma técnica que permite
que um dispositivo responda a
pedidos ARP em nome de outro
dispositivo, permitindo a comunicação
entre redes diferentes.
+ **Exemplo**: um roteador pode responder
a pedidos ARP em nome de um
servidor web, permitindo que os
clientes acessem o servidor.
- **ICMP (Internet Control Message Protocol)**
+ **ICMP**: é um protocolo que permite
enviar mensagens de controle e
erro entre dispositivos em uma rede.
+ **Exemplos**: ping, traceroute, echo request
- **TCP/IP (Transmission Control Protocol/Internet Protocol)**
+ **TCP/IP**: é um conjunto de protocolos
que forma a base da comunicação
na internet.
+ **Exemplos**: TCP (Transmission Control
Protocol), IP (Internet Protocol),
UDP (User Datagram Protocol),
ICMP (Internet Control Message
Protocol)
- **OSI (Open Systems Interconnection) Model**
+ **OSI Model**: é um modelo de
referência para redes de computadores,
dividido em 7 camadas.
+ **Camadas**:
1. Física (Physical)
2. Enlace (Data Link)
3. Rede (Network)
4. Transporte (Transport)
5. Sessão (Session)
6. Apresentação (Presentation)
7. Aplicação (Application)
- **HTTP (Hypertext Transfer Protocol)**
+ **HTTP**: é um protocolo de
comunicação que permite a transferência
de dados na web.
+ **Exemplos**: requisições GET, POST, PUT,
DELETE
0000:8a2e:0370:7334
- **HTTPS (Hypertext Transfer Protocol Secure)**
+ **HTTPS**: é um protocolo de
comunicação que permite a transferência
de dados na web de forma segura.
+ **Exemplos**: requisições GET, POST, PUT,
DELETE com criptografia SSL/TLS

- **FTP (File Transfer Protocol)**
+ **FTP**: é um protocolo de
comunicação que permite a transferência
de arquivos entre servidores.
+ **Exemplos**: upload, download, lista de
arquivos
- **SMTP (Simple Mail Transfer Protocol)**
+ **SMTP**: é um protocolo de
comunicação que permite a transferência
de e-mails entre servidores.
+ **Exemplos**: envio de e-mails, recebimento
de e-mails
- **UDP (User Datagram Protocol)**
+ **UDP**: é um protocolo de
comunicação que permite a transferência
de dados sem garantia de entrega.
+ **Exemplos**: streaming de vídeo, jogos online



