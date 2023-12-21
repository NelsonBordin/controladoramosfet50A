WIki:

https://github.com/NelsonBordin/controladoramosfet50A/wiki/Utilizando-a-Placa-NT500

//========================================================================//
              PROJETO PLACA CONTROLADOR DE MOTOR DC ATE 50A 
                    COM MONITORAMENTO DE AQUECIMENTO
//========================================================================//
  
  AUTOR: NELSON BORDIN JUNIOR
  EMAIL: nelsonbordin@ntronics.com.br / nelsonbordin@hotmail.com

  OBJETIVO DO PROJETO:

  Projeto simples e eficiente para controle de um motor DC com escovas ate 50A com controle de velocidade por PWM e controle de direção.
  O circuito possui uma entrada protegida por Optoacopladores para conexao com circuitos com microcontrolador.
  O circuito possui um sensor de temperatura para monitorar os Mosfets
  O circuito possui um CI 74hc14 para melhorar a eficiencia do Trigger afim de evitar superaquecimento do Mosfet garantindo o chaveamento rápido do Gate
  Possui proteção contra acionamento simultaneo das entradas para evitar curto e danos a fonte e aos mosfets.


  Modulo compacto para uso em aplicações diversas onde é necessário controlar direção e velocidade de um motor DC com escovas de ate 48volts
  O modulo pode trabalhar com ou sem dissipadores de calor ( Vai depender da potencia e da carga do motor acoplado a placa )
  Normalmente um consumo de ate 200Watts ou ate 16Amperes nao há necessidade de dissipador de calor. Vide que o controle das entradas deve ser feito levando em 
  conta a curva de eficiencia do Mosfet IRF44n utilizado no projeto, onde a condução de energia com maior eficiencia e o corte com maior eficiencia encontran-se nas extremidades da 
  tensão no gate.
  Sao utilizados capacitores no circuito do gate para atenuação do ripple da tensao de acionamento. Podem ser modificados de acordo com a necessidade de uso do projeto pelo utilizador.

  Utilize o projeto com responsabilidade e caso seja publicado em sites ou redes sociais por gentileza cite a fonte.
  
//========================================================================//
              PROJECT: DC MOTOR CONTROLLER BOARD UP TO 50A
                       WITH HEATING MONITORING    
//========================================================================//

  AUTHOR: NELSON BORDIN JUNIOR
  EMAIL: nelsonbordin@ntronics.com.br / nelsonbordin@hotmail.com

  PROJECT OBJECTIVE:

  Simple and efficient project for controlling a brushed DC motor up to 50A with PWM speed control and direction control.
  The circuit features an input protected by optocouplers for connection to microcontroller circuits.
  The circuit includes a temperature sensor to monitor the Mosfets.
  The circuit employs a 74hc14 IC to enhance the Trigger efficiency, aiming to prevent Mosfet overheating and ensure quick Gate switching.
  It has protection against simultaneous activation of inputs to prevent short circuits and damage to the power supply and Mosfets.

  Compact module for use in various applications where it is necessary to control the direction and speed of a brushed DC motor up to 48 volts.
  The module can operate with or without heat sinks (depending on the power and load of the motor connected to the board).
  Typically, for a consumption of up to 200 Watts or up to 16 Amperes, there is no need for a heat sink. Note that input control should consider the efficiency curve of the IRF44n Mosfet
  used in the project, where energy conduction with higher efficiency and cutoff with higher efficiency are at the ends of the gate voltage.
  Capacitors are used in the gate circuit for attenuation of the triggering voltage ripple. They can be modified according to the user's project usage needs.

  Use the project responsibly, and if published on websites or social networks, kindly cite the source.
  

  //========================================================================//
