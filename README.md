# Projeto JogoRPG em Java


## Descrição:

Este projeto é parte do curso do ElasTech 2024, oferecido pelo PagBank em parceria com a SoulCode Academy,proposto pelo professor da turma Rafael Gomes.
Consiste na criação de um jogo de RPG simples em Java, onde o jogador interage com o sistema por meio do console.

## Funcionalidades

- O jogador pode escolher entre duas classes de personagens: Guerreiro ou Mago.
- Batalhas baseadas em turnos contra um inimigo representado pela classe Inimigo.
- Exibição de mensagens indicando vitória ou derrota do jogador.
- Lógica orientada a objetos permite fácil extensão do jogo com novas funcionalidades.

## Detalhes das Classes

### Classe JogoRPG
- Método `main(String[] args)`: Ponto de entrada do programa. Cria uma instância da classe Jogo e inicia o jogo chamando o método `iniciarJogo()`.

### Classe Jogo
- Atributos `jogador` e `inimigo`: Representam o jogador e o inimigo no jogo.
- Método `Jogo()`: Construtor da classe que inicializa um jogador e um inimigo.
- Método `iniciarJogo()`: Controla o fluxo do jogo, permitindo que o jogador escolha sua classe e inicie uma batalha contra um inimigo.

### Classe Jogador
- Atributos `vida` e `ataque`: Representam a quantidade de vida e o poder de ataque do jogador.
- Método `Jogador()`: Construtor que inicializa os atributos do jogador.
- Método `atacar(Inimigo inimigo)`: Permite que o jogador ataque o inimigo, reduzindo sua vida.
- Método `estaVivo()`: Verifica se o jogador está vivo com base em sua vida atual.

### Classes Guerreiro e Mago (subclasses de Jogador)
- Métodos `Guerreiro()` e `Mago()`: Construtores que inicializam os atributos específicos de cada classe de jogador.

### Classe Inimigo
- Atributos `vida` e `ataque`: Representam a quantidade de vida e o poder de ataque do inimigo.
- Método `Inimigo()`: Construtor que inicializa os atributos do inimigo.
- Método `atacar(Jogador jogador)`: Permite que o inimigo ataque o jogador, reduzindo sua vida.
- Método `estaVivo()`: Verifica se o inimigo está vivo com base em sua vida atual.

## Pré-requisitos:
- Java Development Kit (JDK) instalado na versão 8 ou superior.
- IDE de desenvolvimento Java, como Eclipse, IntelliJ IDEA, ou NetBeans.
- Conhecimentos básicos de programação em Java.

## Instalação:
1. Clone o repositório para o seu ambiente de desenvolvimento local:
https://github.com/BiancalBarreto/JogoRPG.git
2. Abra o projeto na sua IDE de preferência.
3. Compile e execute o código-fonte do jogo.

## Como Jogar:
1. Execute o jogo a partir da classe principal.
2. Siga as instruções no console para escolher sua classe de personagem e iniciar a batalha.
3. Enfrente o inimigo em turnos, atacando e defendendo conforme necessário.
4. Após a batalha, uma mensagem indicará se você venceu ou foi derrotado.


## História

Em um reino medieval de Valoria, um grande herói terá que enfrentar o terrível dragão Volvagia, que ameaça destruir sua terra. Ele parte em uma jornada perigosa, equipado com sua coragem, habilidade e determinação. Ao chegar à caverna do dragão, um confronto épico se seguiu, com o guerreiro habilidoso esquivando-se das chamas ardentes do dragão e retaliando com golpes precisos de sua espada.


## Personagens:

- Mago Gandolf:
  
  <img src="https://i.pinimg.com/564x/62/c8/1b/62c81bf33cbb05f3ebf268be714db39b.jpg" width="150" height="200"/>
  
- Guerreiro Aragon:
  
  <img src="https://scontent.fssa17-1.fna.fbcdn.net/v/t31.18172-8/12671858_1717557908512095_2952536640627175599_o.jpg?_nc_cat=100&ccb=1-7&_nc_sid=5f2048&_nc_ohc=aIzaMCCoucYAX_o9wQH&_nc_ht=scontent.fssa17-1.fna&oh=00_AfAQOg6nyPLQ4acsvyM4P1uPnQztIAdqOBDMiQYdaV3moA&oe=6630DBC8" width="150" height="200"/>
  
- Dragão Volvagia:
  
  <img src="https://acarajendragons.wordpress.com/wp-content/uploads/2012/08/c1c82-reddragon.jpg" width="200" height="200"/>


## Atributos:

 1. ***Gandolf*** - O Mago:
Pontos de Vida: 150
Itens: magia
Descrição: Gandolf é franzino, mas sua magia é poderosa o suficiente para enfrentar até mesmo os guerreiros mais habilidosos.

2. ***Aragon***- O Guerreiro:
Pontos de Vida: 150
Itens: armadura, espada, escudo 
Descrição: Aragon é robusto e ágil, com uma força incrível capaz de manejar armas pesadas e escudos com facilidade.

### Mago

#### ATAQUE


1.***Raio Gélido***

Dano: 10

Descrição: Você pode disparar um raio capaz de congelar



2.***Bola de Fogo***

Dano: 20

Descrição: Você pode disparar uma esfera de chamas de 20 cm de diâmetro que explode



3.***Trovão***

Dano 20

Descrição: Você pode atirar um raio que cai em cima do seu oponente


4.***Tempestade de Gelo***

Dano: 20

Descrição: Uma chuva de pedaços finos e afiados de gelo cai sobre a área



 #### DEFESA 

 

1.***Proteção Elemental***

Dano: 8

Descrição: Você invoca uma aura protetora que absorve ou neutraliza danos



2.***Manipulação Temporal***

Dano: 10

Descrição: Controle o tempo para desacelerar ou interromper temporariamente o ataque inimigo



3.***Ilusões Defensivas***

Dano: 15

Descrição: Criar ilusões complexas para confundir ou desorientar o dragão



4.***Teleportação***

Dano: 7

Descrição: Se teleportar instantaneamente para escapar de situações perigosas ou de ataques iminentes



### Guerreiro

#### ATAQUE


1.***Golpe Devastador***

Energia: 30 

Dano: 35

Descrição: Ataque corporal de espada



2.***Matador de Dragão***

Dano: 25

Descrição: ataque de machado



3.***Investida Brutal***

Dano: 30

Descrição: executa uma investida rápida e poderosa em direção ao alvo com espada



4.***Corte Furioso***

Dano: 20

Descrição: desfere uma série rápida de golpes de espada



#### DEFESA 


1.***Escudo***

Dano: 2

Descrição: Um escudo grande e resistente para bloquear ataques físicos



2.***Grevas*** 

Dano: 5

Descrição: Ativar proteção para as pernas, cobrindo os pés até abaixo dos joelhos



3.***Elmo*** 

Dano: 10

Descrição: Um elmo robusto para proteger a cabeça contra ataques diretos, como bafo de fogo



4.***Manobras defensivas*** 

Dano: 15

Descrição: Com técnicas de defesa como esquivas, bloqueios e contra-ataque 



## Equipe:

- [Bianca Barreto](https://github.com/BiancalBarreto)
- [Elis Rodrigues](https://github.com/ElisIrons)
- [Érica Viera](https://github.com/ericajv)
- [Emanuelle Cruz](https://github.com/manuscruz)
- [Ingrid](https://github.com/iingrud)
- [Rayla Silva](https://github.com/raylasilva)
- [Rosana Oliveira](https://github.com/SanaOliver)




### Que os jogos comecem!
