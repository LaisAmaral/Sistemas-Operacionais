## Disciplina de Sistemas Operacionais

## Acompanhamento de projetos (Protocolo MQTT) (10/10/18)

Verifique se está ocorrendo um deadlock ou starvation no seu projeto com os seguintes comandos: sudo cat /proc/PID/syscall, sudo cat /proc/PID/task/PID/syscall e strace -s4096 -p PID. Se estiver ocorrendo starvation ou deadlock, o strace tem a palavra futex_wait no resultado e o arquivo syscall contém 202 no primeiro valor. Se não for encontrado starvation ou deadlock, simule um starvation ou deadlock e avalie com esses comandos.. 	 

## Atividade 7 - 	Gerenciamento do armazenamento secundário - sistemas de Arquivos (03/10/18) - Aula 10

- (a) - Utilize o blkid para visualizar cada partição relacionada a seu projeto. (isso inclui o pendrive) (b) - Exemplifique como o stat pode ser útil ao seu projeto. (c) - crie duas partições no pendrive, formate cada uma de forma que uma partição terá blocos de 4k e outra de 64k. Depois avalie o tempo de copiar arquivos em cada partição. *) utilizar o gparted 	 

## Atividade 6 - 	Gerenciamento do Armazenamento Secundário e Sistemas de Arquivos (02/10/18) - Aula 09

Utilize o comando fdisk -l e hdparm -t <disco> para verificar respectivamente as partições e velocidade de leitura dos discos. Exemplifique os comandos no seu projeto: pwd, ls -l, chmod, cd, mkdir, rm, rmdir, mv, cp 
  
 <a href="https://imgur.com/LET0j0w"><img src="https://imgur.com/LET0j0w.jpg" title="source: imgur.com" /></a>
 
 <a href="https://imgur.com/SnyGb4D"><img src="https://imgur.com/SnyGb4D.jpg" title="source: imgur.com" /></a>

## Acompanhamento de projetos (Protocolo MQTT) (02/10/18)


## Acompanhamento de projetos (Protocolo MQTT) (19/09/18)

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


## Atividade 5 - Definir o Cenário contendo dispositivos de entrada e saída (18/09/18)

<a href="https://imgur.com/ftz6XYE"><img src="https://imgur.com/ftz6XYE.jpg" title="source: imgur.com" /></a>

<a href="https://imgur.com/PozjqMp"><img src="https://imgur.com/PozjqMp.jpg" title="source: imgur.com" /></a>


## Atividade 4 - Systems Calls (11/09/18)

<a href="https://imgur.com/c0YIzh9"><img src="https://imgur.com/c0YIzh9.jpg" title="source: imgur.com" /></a>
Criação de system call saida.txt e systemscalls.txt


<a href="https://imgur.com/gUL1GZJ"><img src="https://imgur.com/gUL1GZJ.jpg" title="source: imgur.com" /></a>
Arquivos já criados


<a href="https://imgur.com/FtSgbxP"><img src="https://imgur.com/FtSgbxP.jpg" title="source: imgur.com" /></a>
Arquivo saida.txt na pasta pessoal


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
              
