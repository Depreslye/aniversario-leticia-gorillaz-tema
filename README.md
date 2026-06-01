
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Feliz Aniversário!</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial, Helvetica, sans-serif;
    background:#111;
    color:white;
    overflow-x:hidden;
}

header{
    min-height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    background:
    linear-gradient(rgba(0,0,0,.65),rgba(0,0,0,.65)),
    url("foto-capa.jpg");
    background-size:cover;
    background-position:center;
}

header h1{
    font-size:4rem;
    text-shadow:0 0 20px #ff0055;
}

header h2{
    margin-top:10px;
    font-size:2rem;
    color:#00e5ff;
}

header p{
    margin-top:20px;
    max-width:700px;
    font-size:1.2rem;
}

.btn{
    margin-top:30px;
    padding:15px 30px;
    border:none;
    border-radius:30px;
    background:#ff0055;
    color:white;
    font-size:1rem;
    cursor:pointer;
    transition:.3s;
}

.btn:hover{
    transform:scale(1.08);
}

section{
    padding:80px 10%;
}

.titulo{
    text-align:center;
    margin-bottom:40px;
    font-size:2.5rem;
}

.mensagem{
    max-width:800px;
    margin:auto;
    text-align:center;
    font-size:1.2rem;
    line-height:1.8;
}

.galeria{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.galeria img{
    width:100%;
    height:300px;
    object-fit:cover;
    border-radius:20px;
    transition:.3s;
}

.galeria img:hover{
    transform:scale(1.04);
}

.card{
    background:#1d1d1d;
    border-radius:20px;
    padding:25px;
    text-align:center;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

footer{
    text-align:center;
    padding:40px;
    background:#0a0a0a;
}

#surpresa{
    display:none;
    margin-top:30px;
    background:#222;
    padding:20px;
    border-radius:15px;
}

.confete{
    position:fixed;
    width:10px;
    height:10px;
    top:-10px;
    animation:cair linear infinite;
}

@keyframes cair{
    to{
        transform:translateY(110vh) rotate(720deg);
    }
}
</style>
</head>

<body>

<header>

<h1>🎉 FELIZ ANIVERSÁRIO 🎉</h1>

<h2>leticia</h2>

<p>
You won't get undercounted 'cause you're damned and free.
</p>

<button class="btn" onclick="abrirSurpresa()">
🎁 Abrir Mensagem Especial
</button>

<div id="surpresa">
<h3>✨ Mensagem Especial ✨</h3>

<p>
Vai ficar tudo bem no final. E se não ficar, não é o fim! -2d
</p>

</div>

</header>

<section>

<h2 class="titulo">🎸 Galeria da Festa</h2>

<div class="galeria">

<img src="https://i.pinimg.com/736x/c7/4a/83/c74a83bf253c62923b58a588b98aa932.jpg" alt="">
<img src="https://i.pinimg.com/736x/fc/f3/5e/fcf35e425cde24c853ad91d1d25f0e04.jpg" alt="">
<img src="https://i.pinimg.com/736x/e5/5d/d4/e55dd4e3a6fffaeeb52a023c0339b1d1.jpg" alt="">
<img src="https://i.pinimg.com/736x/7f/7f/78/7f7f781df8b3b7e4c1a29ceb43cb04cd.jpg" alt="">

</div>

</section>

<section>

<h2 class="titulo">⭐ Destaques do Dia</h2>

<div class="cards">

<div class="card">
<h3>🎂 Bolo</h3>
<p>Hora de apagar as velas e fazer um pedido.</p>
</div>

<div class="card">
<h3>🎵 Música</h3>
<p>Uma playlist especial para curtir a comemoração.</p>
</div>

<div class="card">
<h3>📸 Memórias</h3>
<p>Guardar momentos que serão lembrados por anos.</p>
</div>

</div>

</section>

<section>

<h2 class="titulo">💜 clint eastwood</h2>

<div class="mensagem">

<p>
Finally, someone let me out of my cage
Now time for me is nothing 'cause I'm countin' no age
Nah, I couldn't be there, now you shouldn't be scared
I'm good at repairs (it's all simple), and I'm under each snare.
</p>

</div>

</section>

<footer>

<p>🎉 Feliz Aniversário! 🎉</p>
<p>Feito especialmente para este dia especial.</p>

</footer>

<script>

function abrirSurpresa(){
    document.getElementById("surpresa").style.display="block";
}

for(let i=0;i<120;i++){

    const c=document.createElement("div");

    c.classList.add("confete");

    c.style.left=Math.random()*100+"vw";

    c.style.animationDuration=
    (Math.random()*5+4)+"s";

    c.style.opacity=Math.random();

    c.style.background=
    `hsl(${Math.random()*360},100%,50%)`;

    document.body.appendChild(c);
}

</script>

</body>
</html>
<section>
  <h2>🎵 Playlist da Festa</h2>

  <iframe
    style="border-radius:12px"
    src="https://open.spotify.com/playlist/5137tjFBaaMh9dcH8i9fHR?si=ae61988a16a74cb4"
    width="100%"
    height="352"
    frameborder="0"
    allowfullscreen=""
    allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture">
  </iframe>
</section>  
