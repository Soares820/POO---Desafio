# Projeto iPhone - Modelagem e Implementação

Este projeto tem como objetivo modelar e implementar as funcionalidades do iPhone, abrangendo três componentes principais: **Reprodutor Musical**, **Aparelho Telefônico** e **Navegador na Internet**. A modelagem foi realizada utilizando UML, e a implementação foi feita em Java.

## Diagrama UML

O diagrama UML representa as classes e interfaces que compõem o sistema. Abaixo está a estrutura do diagrama:
+---------------------+ | iPhone | +---------------------+ | - musicPlayer: MusicPlayer | | - telefone: Telefone | | - navegador: InternetBrowser | +---------------------+ | + playMusic() | | + makeCall() | | + browseInternet() | +---------------------+









+---------------------+ | Leitor de música | +---------------------+ | + tocar() | | + pausa() | | + selecionarMúsica(música: String) | +---------------------+





+---------------------+ | Telefone | +---------------------+ | + ligar(número: String) | | + atender() | | + iniciarCorreioVoz() | +---------------------+





+---------------------+ | Navegador de Internet | +---------------------+ | + exibirPagina(url: String) | | + adicionarNovaAba() | | + atualizarPagina() | +---------------------+









texto

## Funcionalidades

- **Reprodutor Musical**
  - `tocar()`: Inicia a reprodução de música.
  - `pausar()`: Pausa a música em reprodução.
  - `selecionarMusica(String musica)`: Seleciona uma música específica para tocar.

- **Aparelho Telefônico**
  - `ligar(String numero)`: Realiza uma chamada para o número especificado.
  - `atender()`: Atende uma chamada recebida.
  - `iniciarCorreioVoz()`: Inicia o serviço de correio de voz.

- **Navegador na Internet**
  - `exibirPagina(String url)`: Exibe a página da web especificada.
  - `adicionarNovaAba()`: Adiciona uma nova aba no navegador.
  - `atualizarPagina()`: Atualiza a página atual exibida.

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

- **MusicPlayer.java**: Interface que define os métodos do reprodutor musical.
- **Telephone.java**: Interface que define os métodos do aparelho telefônico.
- **InternetBrowser.java**: Interface que define os métodos do navegador na internet.
- **iPhone.java**: Classe que implementa as interfaces e agrega as funcionalidades.
