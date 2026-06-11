<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A Importância do Café em Pinhalão - PR</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    background: linear-gradient(135deg,#2e1a08,#5c3317,#8b4513);
    color:#ffffff;
    line-height:1.7;
}

header{
    text-align:center;
    padding:40px 20px;
    background:rgba(0,0,0,0.35);
}

header h1{
    font-size:2.8rem;
    color:#FFD700;
    text-shadow:2px 2px 5px black;
}

header p{
    font-size:1.2rem;
    margin-top:10px;
}

.autora{
    background:#FFD700;
    color:#000;
    display:inline-block;
    padding:8px 18px;
    border-radius:30px;
    margin-top:15px;
    font-weight:bold;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
    padding:30px 0;
}

.imagem{
    text-align:center;
    margin:25px 0;
}

.imagem img{
    width:100%;
    max-width:850px;
    border-radius:20px;
    border:5px solid #FFD700;
    box-shadow:0 0 20px rgba(255,215,0,0.6);
}

.card{
    background:rgba(255,255,255,0.1);
    backdrop-filter:blur(5px);
    padding:25px;
    border-radius:20px;
    margin:25px 0;
    border:2px solid #FFD700;
}

.card h2{
    color:#FFD700;
    margin-bottom:15px;
}

.emoji-area{
    text-align:center;
    margin-top:20px;
}

.emoji{
    font-size:3rem;
    cursor:pointer;
    margin:10px;
    transition:0.4s;
}

.emoji:hover{
    transform:scale(1.3) rotate(10deg);
}

.mensagem{
    margin-top:15px;
    font-size:1.2rem;
    color:#FFFF99;
    font-weight:bold;
}

.botao{
    display:block;
    margin:25px auto;
    padding:15px 25px;
    border:none;
    border-radius:10px;
    background:#FFD700;
    color:#000;
    font-size:1rem;
    font-weight:bold;
    cursor:pointer;
}

.botao:hover{
    background:#fff176;
}

footer{
    text-align:center;
    background:rgba(0,0,0,0.4);
    padding:20px;
    margin-top:30px;
}

@media(max-width:768px){
    header h1{
        font-size:2rem;
    }

    .emoji{
        font-size:2.3rem;
    }
}
</style>
</head>

<body>

<header>
    <h1>☕ A Importância do Café em Pinhalão - PR ☕</h1>
    <p>O café é uma das riquezas agrícolas do Norte Pioneiro do Paraná.</p>

    <div class="autora">
        ✨ Autora: Ana Letícia - Colégio Leonardo Francisco Nogueira ✨
    </div>
</header>

<div class="container">

    <div class="imagem">
        <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&w=1200&q=80"
             alt="Cafezal com frutos vermelhos na colheita">
    </div>

    <div class="card">
        <h2>🌱 Café e Agricultura</h2>

        <p>
            O município de Pinhalão, localizado no Norte Pioneiro do Paraná,
            possui grande tradição na produção de café. O cultivo gera emprego,
            movimenta a economia local e valoriza o trabalho das famílias rurais.
        </p>

        <p>
            Os grãos vermelhos indicam o ponto ideal da colheita e contribuem
            para a produção de cafés de alta qualidade, reconhecidos em diversas regiões.
        </p>
    </div>

    <div class="card">
        <h2>🎯 Clique nos Emojis para Aprender</h2>

        <div class="emoji-area">
            <span class="emoji" onclick="mostrarMensagem('☕ O café é uma das principais culturas agrícolas da região.')">☕</span>

            <span class="emoji" onclick="mostrarMensagem('🌱 O cultivo do café gera renda para muitas famílias rurais.')">🌱</span>

            <span class="emoji" onclick="mostrarMensagem('🚜 A agricultura fortalece a economia de Pinhalão.')">🚜</span>

            <span class="emoji" onclick="mostrarMensagem('❤️ Os grãos vermelhos representam qualidade e dedicação dos produtores.')">❤️</span>

            <div class="mensagem" id="mensagem">
                Clique em um emoji!
            </div>
        </div>
    </div>

    <div class="card">
        <h2>📚 Curiosidade</h2>

        <p>
            O Norte Pioneiro do Paraná é conhecido pela produção de cafés especiais,
            que recebem reconhecimento pela qualidade dos grãos, aroma e sabor.
        </p>

        <button class="botao" onclick="curiosidade()">
            Descobrir Curiosidade ☕
        </button>

        <p id="curiosidade"></p>
    </div>

</div>

<footer>
    <h3>☕ Café: tradição, trabalho e desenvolvimento para Pinhalão - PR ☕</h3>
    <p>Projeto Escolar desenvolvido por Ana Letícia - Colégio Leonardo Francisco Nogueira</p>
</footer>

<script>

function mostrarMensagem(texto){
    document.getElementById("mensagem").innerHTML = texto;
}

function curiosidade(){

    const curiosidades = [
        "☕ Um pé de café pode produzir por muitos anos quando bem cuidado.",
        "🌱 Os frutos vermelhos indicam o momento ideal para a colheita.",
        "🚜 O café ajuda a movimentar a economia do Norte Pioneiro.",
        "🏆 A região é reconhecida pela produção de cafés especiais.",
        "🌎 O café brasileiro é apreciado em diversos países."
    ];

    const sorteio =
    curiosidades[Math.floor(Math.random()*curiosidades.length)];

    document.getElementById("curiosidade").innerHTML = sorteio;
}

</script>

</body>
</html>
