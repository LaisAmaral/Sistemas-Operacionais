## Disciplina de Sistemas Operacionais

## Atividade 6 - Subprocessos e acompanhamento de projetos (19/09/18)

Acompanhamento de projetos:

<a href="https://imgur.com/qJ0CIim"><img src="https://imgur.com/qJ0CIim.jpg" title="source: imgur.com" /></a>

Mosquitto é um módulo em python que oferece as funcionalidades do MQTT.
Use o mosquitto_sub p/ assinar um tópico e o mosquitto_pub para publicar.

mosquitto_sub -h localhost -t "testtopic" -v (Tópico assinado)
  
mosquitto_pub -h localhost -t "testtopic" -m "Testing" (Postagem no tópico, KDE do Konsole 2,aonde é possível verificar que consta no KDE do Konsole 1).

sudo service mosquitto status (Verificação de status do mosquitto)
 
É possível utilizar:
 
sudo service mosquitto start (iniciar),
sudo service mosquitto stop  (parar) e
sudo service mosquitto restart (reiniciar)


## Atividade 5 - Entrada e Saída (18/09/18)

<a href="https://imgur.com/ftz6XYE"><img src="https://imgur.com/ftz6XYE.jpg" title="source: imgur.com" /></a>

<a href="https://imgur.com/PozjqMp"><img src="https://imgur.com/PozjqMp.jpg" title="source: imgur.com" /></a>


## Atividade 4 - Systems Calls (11/09/18)

## Atividade 3: Definir Cenário Geral e Realizar Alteraçoes (05/09/18)

Cenário Geral: <br/>

5 Itens que serão alterados: <br/>

Tabela com 10 experimento com o comando time para cada item: <br/>

<a href="https://imgur.com/nJnef2O"><img src="https://imgur.com/nJnef2O.jpg" title="source: imgur.com" /></a>)


## Atividade 2: Gravação da instalação do ambiente (04/09/18)

Neste vídeo mostramos a instalação, por linha de comando, do Servidor e Cliente Mosquitto.

sudo apt-get install mosquitto
sudo apt-get install mosquitto-clients

Video :https://www.youtube.com/watch?v=K2IsVngCcDc <br/>

[![](https://img.youtube.com/vi/K2IsVngCcDc/0.jpg)](https://www.youtube.com/watch?v=K2IsVngCcDc)

<br/>

Simulação de teste de comunicação do Protocolo MQTT.

Video :https://www.youtube.com/watch?v=1WYMytqY4DU <br/>

[![](https://img.youtube.com/vi/1WYMytqY4DU/0.jpg)](https://www.youtube.com/watch?v=1WYMytqY4DU)

<br/>

## Atividade 1: Instalação do VM, do Debian e Definição do Tema (29/08/18)

Tema do Projeto: MQTT

Alunos: Tiago Ribeiro, Lais Amaral e Leticia Miranda

Protocolo MQTT

O MQTT é um protocolo de rede leve e flexível que oferece o equilíbrio ideal para os desenvolvedores de IoT:

O protocolo leve permite a implementação em hardware de dispositivo altamente restringido e em redes de largura da banda limitada e de alta latência.
Sua flexibilidade possibilita o suporte a diversos cenários de aplicativo para dispositivos e serviços de IoT.
Para entender por que o MQTT é tão adequado para desenvolvedores de IoT, vamos analisar por que outros protocolos de rede populares falharam em IoT.

Referências: https://www.ibm.com/developerworks/br/library/iot-mqtt-why-good-for-iot/index.html
             https://www.embarcados.com.br/mqtt-protocolos-para-iot/
             https://www.dobitaobyte.com.br/iot-configurando-um-mqtt-broker/
              
