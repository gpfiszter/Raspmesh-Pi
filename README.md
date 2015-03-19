# Raspmesh-Pi
Raspmesh pi � um projeto de nodes para rede mesh utilizando Raspberry Pi alimentados com energia solar
## Materiais Necessarios
- Raspberry Pi B+
- Dissipador de calor
- Cart�o SD
- Adapdator de rede WiFi
- Placa Fotovoltaica 5W
- Controlador de carga
- Bateria 5V
- Caixa herm�tica vedada

##Protocolos de roteamento em mesh
###OLSR
O protocolo **Optimized Link State Routing Protocol** � um protocolo desnvolvidos para redes MANETs que tamb�m pode ser utilisado em redes mesh, ele utiliza mensagens de *hello* e *Topology Control* para disseminar e descobrir o status dos links.
###B.A.T.M.A.N.
O protocolo **Better Approach To Mobile Adhoc Networking** � protocolo criado para substituir o protocolo **OLSR**. Sua pricipal vantagem � a sua de descentraliza��o, que torna poss�vel que cada note apenas receba informa��es da "dire��o" de onde os dados foram recebidos e os passe de acordo para o pr�ximo ponto.