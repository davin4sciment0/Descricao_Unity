# Jogo do Astronauta

<a href="https://youtu.be/GNJCFnRgIXw" target="_blank">Clique aqui para assistir ao jogo</a>

<a href="https://drive.google.com/drive/folders/1aRXR83QR8oAexbKWf9EYqxdAwfOsTy51?usp=sharing" target="_blank">Clique aqui para baixar e jogar</a>

### Autores
Davi dos Santos Nascimento e João Lucas dos Anjos Pinto

Esta cena foi criada com o intuito de aprendermos as colisões: Static collider, Rigidbody Collider, Kinematic Rigidbody Collider, Static Trigger Collider, Rigidbody Trigger Collider, onde conseguimos aplicar isso em nossa cena de maneira bem intuitiva.

## Player:
Utilizamos um Astronauta como Player onde emsi já possuium Capsule Collider e um Rigidbody como deve ser feito, além disso, implementamos a ele os scripts necessários para o desenrolar da cena.
<div>
     <img src="img/Player.jpg" width="200px"> 
     <img src="img/Braco.jpg" width="300px"> 
</div>

<img src="img/Player_Config.jpg" width="500px">

## Cenário
Ao longo do cenário colocamos diversas plataformas e desafios para o jogador percorrer
<img src="img/Cenario.jpg" width="700px">

### Componentes do cenário

<img src="img/Area_de_salto.jpg" width="180px"> <img src="img/Estrelas.jpg" width="212px"> <img src="img/Gosma.jpg" width="190px"> <img src="img/Limitador.jpg" width="218px"> <img src="img/Plataformas.jpg" width="170px">

## Códigos usados:
Aqui estaremos mostrando alguns dos códigos essenciais para realização do projeto. Onde criamos e colocamos os Scripts no Player, para que as colisões ocorrecem da maneira correta, precisariamos detectar os objetos (através de suas tag's) que estariam em colisão e assim executar uma função dependendo do contexto, a partir dai conseguimos executar os tipos de colisões solicitadas.

<img src="img/Script1.jpg" width="600px"> 
<img src="img/Script2.jpg" width="600px"> 
<img src="img/Script3.jpg" width="600px"> 

### Colisores
## Static collider:
Representa objetos que não se movem durante a execução do jogo. Esses objetos são imutáveis em termos de posição e forma ao longo do tempo de jogo. 

("utilizado para a colisão de parede e outros na cena").

## Rigidbody Collider: 
Este componente é usado para aplicar física a um objeto. Quando um objeto tem um Rigidbody associado, ele passa a ser afetado pela gravidade, forças externas e pode ter movimento físico. 

("utilizado no personagem").

## Kinematic Rigidbody Collider
Este tipo de colisor foi projetado para se mover sob simulação, mas apenas sob controle muito explícito do usuário. Enquanto um Corpo Rígido Dinâmico é afetado pela gravidade e forças, um Corpo Rígido Cinemático não é. 

## Static Trigger Collider: 
Pode-se unir o Trigger Colliders, um tipo especial de Collider, que não gera uma resposta física quando dois objetos colidem, mas, em vez disso, dispara eventos quando um objeto entra ou sai de sua área de colisão, em objetos estáticos (objetos que não se movem).

("utilizado nas estrelas vermelhas")

## Rigidbody Trigger Collider:
Ao combinar um Rigidbody com um Trigger Collider, você pode criar situações em que objetos com Rigidbody podem acionar eventos quando entram em contato com a área de detecção do Trigger Collider, mesmo que não haja uma resposta física associada à colisão. 

("utilizado na área de impulssão")
