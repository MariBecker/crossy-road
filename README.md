![cow](/imagens/ator-1.png) 
# Crossy-Road



Crossy-Road é um jogo onde o jogador deve atravessar a rua enquanto desvia dos carros em movimento. É um projeto desenvolvido no curso da 
[Alura](http://alura.com.br), jogos clássicos parte II. Para deselvolver esse projeto, utilizei o Framework P5.js. O projeto original não permitia que o jogador fosse para esquerda e direita, com isso, implementei o código para seguir esses comandos também.

```javascript

if (keyIsDown(LEFT_ARROW)) {
    xAtor -= 3;
}
if (keyIsDown(RIGHT_ARROW)) {
    xAtor += 3;
}
  ```
  
  Caso o jogador consiga atravessar a rua sem colidir, é marcado um ponto, caso o jogador colida em algum carro, é retirado um ponto.
