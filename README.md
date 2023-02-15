# Scratch3 for IOT

Arduino, Raspberry Pi, ESP-8266, Raspberry Pi Pico,
Picoboard, Circuit Playground Express,
RoboHAT MM1

## Resumo em Português do manual: https://mryslab.github.io/s3-extend/

Controle o seu microcontrolador favorito usando o Scratch 3.


    - Sistemas Operativos Suportados: Windows, Mac e Linux, incluindo o Raspberry Pi (ARM).

    - Corra o Scratch 3 via the internet ou localmente no seu computador.

    - Controle o seu Raspberry Pi localmente ou do seu PC.


# O que precisa e como instalar a extensão

- Para utilizadores do Windows: Instale o Python antes
- Instale o pip fazendo: sudo apt install python3-pip
- Actualize o pip caso o tenha: pip3 install --upgrade pip
- Instale a extensão: pip3 install s3-extend

# Prepare o seu microcontrolador
- Arduino And RoboHAT MM1 - Using Arduino IDE
    - Instale a FirmataExpress, em Tools/Manage Libraries
    - Instale a Ultrasonic Library by Erick Simões, Tools/Manage Libraries
    - Compile e envie o FirmataExpress para o Arduino
        - Seleccione File/Examples e na lista, escolha FirmataExpress.
        - Depois faça enviar para o arduino (verifique se é a porta correta: ex: /dev/ttyACM0)
- ESP-8266 NodeMCU
    - No Arduino IDE instale a Telemetrix4ESP8266 Sketch em Tools/Manage Libraries
    - Abra o ficheiro ino Telemetrix4ESP8266 e configure os parâmetros da rede: SSID e palavra-passe
    - Verifique o endereço IP Address no ESP-8266, usando o monitor série do Arduino IDE
- Raspbery PI
    - Apenas precisa de ter instalado a extensão s3-extend

# Como usar as extensões OneGPIO

- Ligue o microcontrolador à alimentação

- Execute na linha de comandos, o comando correspondente ao controlador:
    - s3a - for the Arduino
    - s3c - for the Adafruit Circuit Playground Express
    - s3e - for the ESP-8266
    - s3p - for the Picoboard
    - s3pup - for the Pupper Robot
    - s3r - for the Raspberry Pi
    - s3rp for the Raspberry Pi Pico
    - s3rh - for the RoboHAT MM1
    
Em linux: s3a -c /dev/ttyACM0

# Como correr o Scratch
O navegador de internet recomendado para o Scratch3 OneGPIO extensions é o Google Chrome.

## Online
Abrir a ligação no navegador: https://mryslab.github.io/s3onegpio/ e depois adicionar o controlador.

## Offline
- Fazer o download da ligação: https://github.com/MrYsLab/s3onegpio/archive/refs/heads/gh-pages.zip
- Extraia os ficheiros comprimidos
- Execute o ficheiro index.html com o Google Chrome 

# Blocos do Arduino
![ard_blocks](https://user-images.githubusercontent.com/43177468/218227542-da131d73-b084-4b05-a88a-836a34cd883c.png)
