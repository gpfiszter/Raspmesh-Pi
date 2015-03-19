# Raspmesh-Pi
Raspmesh pi é um projeto de nodes para rede mesh utilizando Raspberry Pi alimentados com energia solar
## Materiais Necessarios
- Raspberry Pi B+
- Dissipador de calor
- Cartão SD
- Adapdator de rede WiFi
- Placa Fotovoltaica 5W
- Controlador de carga
- Bateria 5V
- Caixa hermética vedada

##Protocolos de roteamento em mesh
###OLSR
O protocolo **Optimized Link State Routing Protocol** é um protocolo desnvolvidos para redes MANETs que também pode ser utilisado em redes mesh, ele utiliza mensagens de *hello* e *Topology Control* para disseminar e descobrir o status dos links.
###B.A.T.M.A.N.
O protocolo **Better Approach To Mobile Adhoc Networking** é protocolo criado para substituir o protocolo **OLSR**. Sua pricipal vantagem é a sua de descentralização, que torna possível que cada note apenas receba informações da "direção" de onde os dados foram recebidos e os passe de acordo para o próximo ponto.