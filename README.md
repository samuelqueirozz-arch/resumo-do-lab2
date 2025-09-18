# resumo-do-lab2

Computação de Rede – Resumo Azure

VNet (Virtual Network):
Rede virtual no Azure, equivalente a uma rede local, onde ficam os recursos (VMs, bancos etc.).

Sub-rede (Subnet):
Segmenta a VNet em partes menores para organizar serviços e aplicar regras de segurança.

NSG (Network Security Group):
Firewall de rede que controla tráfego de entrada e saída por meio de regras.

VNet Peering:
Conecta duas VNets diferentes para que se comuniquem pela rede backbone da Microsoft.

VPN (Virtual Private Network):
Conecta a rede local ao Azure via internet, com criptografia.

ExpressRoute:
Conexão privada e dedicada entre rede local e Azure (não passa pela internet).

Load Balancer:
Distribui tráfego entre várias VMs para aumentar disponibilidade.

Application Gateway:
Balanceador de carga de nível de aplicação (Camada 7) com WAF para proteger aplicações web.

👉 Em resumo:

VNet + Sub-rede → estrutura de rede

NSG → segurança

Peering → comunicação entre VNets

VPN/ExpressRoute → integração com rede local

Load Balancer/App Gateway → alta disponibilidade e proteção
