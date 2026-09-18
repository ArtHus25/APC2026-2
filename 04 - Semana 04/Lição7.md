# LIÇÃO 7: TEXT

```JavaScript
World.frameRate = 10;
function draw() {
  // Background e lava
  var fundo = createSprite(200,100);
  fundo.setAnimation("fundo");
  var lava = createSprite(randomNumber(60,360),360);
  lava.setAnimation("lava");
  var lava1 = createSprite(randomNumber(60,360),362);
  lava1.setAnimation("lava");
  var lava2 = createSprite(randomNumber(60,360),362);
  lava2.setAnimation("lava");
  var lava3 = createSprite(randomNumber(60,360),362);
  lava3.setAnimation("lava");
  var lava4 = createSprite(randomNumber(60,360),362);
  lava4.setAnimation("lava");
  var lava5 = createSprite(randomNumber(60,360),362);
  lava5.setAnimation("lava");
  // Monstro e a Banana
  var monstro = createSprite();
  monstro.x = 100;
  monstro.y = randomNumber(180,200);
  monstro.setAnimation("monstro");
  monstro.scale = 0.3;
  var banana = createSprite();
  banana.x = 300;
  banana.y = 200;
  banana.setAnimation("banana");
  banana.scale = 0.3;
  banana.rotation = randomNumber(0,360);
  drawSprites();
  // Texto
  fill("red");
  stroke("black");
  strokeWeight(10);
  textSize(15);
  text("Its realy Hot",60,90);
  text("in here!!!",70,120);
  fill("yellow");
  stroke("green");
  strokeWeight(10);
  textSize(30);
  text("BANANA!!!",220,100);
}
```

Nesse Desafio foi preciso criar um cena com um texto para criar um interação entre dois personagens, minha maior dificuldade foi como encaixar a mensagem sem que atrapalhasse os personagens. Foi um desafio até simples mas bem divertido. No marcador //Texto no código mostra as especificações do texto como tamanho, cor e localização do texto na imagem.