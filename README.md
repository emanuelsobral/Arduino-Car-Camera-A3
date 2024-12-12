# Arduino-Car-Camera-A3
Arduino Car With Camera


# Credits of the code base

  Rui Santos
  Complete instructions at https://RandomNerdTutorials.com/esp32-cam-projects-ebook/
  
  Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files.
  The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

# Robô com Câmera ESP32 - Versões 1 e 2

# Descrição Geral:

 Este projeto apresenta um robô móvel equipado com uma câmera ESP32-CAM, controlado remotamente através de uma interface web. São apresentadas duas versões do projeto:

# Versão 1: Host Local
 O robô cria um ponto de acesso Wi-Fi próprio para que o usuário se conecte diretamente a ele.
# Versão 2: Conexão Wi-Fi
 O robô se conecta a uma rede Wi-Fi existente, permitindo o controle remoto de qualquer dispositivo conectado à mesma rede.

# Hardware:

   Microcontrolador ESP32: Coração do projeto, responsável por controlar todos os componentes e processar as informações da câmera.
   Módulo ESP32-CAM: Combina uma câmera OV2640 ou OV7670 com o microcontrolador ESP32, simplificando a integração de visão computacional.
   Driver de motor L298N: Controla os dois motores DC do robô, permitindo movimentos para frente, para trás, esquerda e direita.
   Motores DC: Impulsionam o robô, proporcionando a locomoção.  
   Fonte de alimentação: Bateria ou fonte externa para alimentar o ESP32 e os motores.
   Placa de prototipagem (opcional): Facilita a montagem e a conexão dos componentes.

# Software:

Arduino IDE: Ambiente de desenvolvimento utilizado para programar o ESP32.
   Bibliotecas:
       ESP32 Camera: Responsável por controlar a câmera e capturar imagens.
       WiFi.h: Permite a conexão do ESP32 à rede Wi-Fi.
       Esp32 HTTP Server: Cria um servidor web para a interface de controle.
   Linguagem: C++
   
# Funcionalidades:

   Transmissão de vídeo em tempo real: A câmera captura imagens continuamente e as transmite para um navegador web, proporcionando uma visão em primeira pessoa do ambiente.
   Controle remoto: Através de uma interface web intuitiva, é possível controlar os movimentos do robô usando botões ou as teclas WASD do teclado.
   Conexão Wi-Fi: O robô se conecta a uma rede Wi-Fi existente, permitindo o controle remoto de qualquer dispositivo conectado à mesma rede.
   Flexibilidade: O código pode ser facilmente adaptado para implementar funcionalidades adicionais, como detecção de objetos, seguimento de linha ou controle por aplicativo móvel.

# Como usar:

   Monte o hardware: Conecte os componentes de acordo com o diagrama esquemático.
   Carregue o código: Abra o projeto no Arduino IDE, configure as credenciais da sua rede Wi-Fi e carregue o código para o ESP32.
   Conecte-se à rede Wi-Fi: Conecte seu dispositivo (smartphone, computador) à mesma rede Wi-Fi que o robô.
   Acesse a interface web: Abra um navegador e digite o endereço IP do ESP32 (informado no monitor serial) para controlar o robô.

# Observações:

   Personalização: Você pode personalizar o código para ajustar a resolução da câmera, a taxa de quadros, os comandos de controle e outras configurações.
   Segurança: Ao conectar o robô a uma rede Wi-Fi, é importante tomar precauções de segurança para evitar acessos não autorizados.
   Expansão: O projeto pode ser expandido com a adição de sensores, atuadores e outros componentes para criar funcionalidades mais avançadas.

# Próximos passos:

   Detecção de obstáculos: Implementar algoritmos de visão computacional para detectar obstáculos e evitar colisões.
   Seguimento de linha: Fazer com que o robô siga uma linha preta sobre um fundo branco.
   Controle por aplicativo móvel: Desenvolver um aplicativo para controlar o robô a partir de um smartphone.

# Contribuições:

Contribuições para este projeto são bem-vindas! Se você tiver alguma sugestão, correção ou nova funcionalidade, sinta-se à vontade para abrir um pull request.

# Pacotes Arduino

http://arduino.esp8266.com/stable/package_esp8266com_index.json
https://dl.espressif.com/dl/package_esp32_index.json
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
