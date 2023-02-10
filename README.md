# Scratch3 for IOT

Arduino, Raspberry Pi, ESP-8266, Raspberry Pi Pico,
Picoboard, Circuit Playground Express,
RoboHAT MM1

## Resumo em Português do manual: https://mryslab.github.io/s3-extend/

Control your favorite physical computing device using Scratch 3.


    - Windows, Mac, **and Linux, including Raspberry Pi, are supported.**

    - Launch Scratch 3 via the internet or locally on your computer.

    - Control your Raspberry Pi either locally or from your PC.


# Como Instalar
Se desejar instalar o scratch3 use os links: 
- Windows e Mac: https://scratch.mit.edu/download/
- Linux: https://scratux.org/#download ou https://github.com/redshaderobotics/scratch3.0-linux/releases/tag/1.2.1

# Como instalar a extensão
https://mryslab.github.io/s3-extend/#



## Simple Python Version Management: pyenv
https://github.com/pyenv/pyenv#installation

pyenv lets you easily switch between multiple versions of Python. It's simple, unobtrusive, and follows the UNIX tradition of single-purpose tools that do one thing well.

Installation
git clone https://github.com/pyenv/pyenv.git ~/.pyenv
Define environment variable PYENV_ROOT to point to the path where pyenv repo is cloned and add $PYENV_ROOT/bin to your $PATH for access to the pyenv command-line utility.

For Ubuntu Desktop:
$ echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bashrc
$ echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bashrc

user:~$ python3 -V
Python 3.6.9

$ pyenv install 3.7.7

Se for necessário usar:
python3 -m pip install --user --upgrade pip

Caso seja necessário faça o update do python para a versão 3.7 seguindo:
https://tecadmin.net/install-python-3-6-ubuntu-linuxmint/

instalar pip
- curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
- python get-pip.py --user
