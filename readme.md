<header class="cabecalho">
    <div class="overlay">
        <h1>AGRINHO 2026</h1>

        <h2>AGRO FORTE: DESENVOLVIMENTO E SUSTENTABILIDADE</h2>

        <div class="informacoes">
            <p><strong>PROFESSORA ORIENTADORA:</strong> LUCIANA PEREIRA</p>

            <p><strong>INSTITUIÇÃO:</strong> COLÉGIO ESTADUAL LEONARDO FRANCISCO NOGUEIRA</p>

            <p><strong>MUNICÍPIO:</strong> PINHALÃO - PARANÁ</p>
        </div>
    </div>
</header>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Segoe UI',sans-serif;
}

.cabecalho{
    height:100vh;
    background:linear-gradient(
        rgba(0,50,100,0.75),
        rgba(0,100,180,0.75)
    ),
    url('https://images.unsplash.com/photo-1500937386664-56d1dfef3854');
    background-size:cover;
    background-position:center;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
}

.overlay{
    max-width:1000px;
    padding:40px;
}

h1{
    font-size:5rem;
    letter-spacing:6px;
    text-transform:uppercase;
    margin-bottom:20px;
    text-shadow:3px 3px 10px rgba(0,0,0,0.4);
}

h2{
    font-size:2rem;
    text-transform:uppercase;
    margin-bottom:40px;
    color:#bde7ff;
}

.informacoes{
    background:rgba(255,255,255,0.12);
    backdrop-filter:blur(10px);
    padding:30px;
    border-radius:20px;
}

.informacoes p{
    font-size:1.2rem;
    margin:15px 0;
  
    letter-spacing:1px;
    text-transform:uppercase;
}

strong{
    color:#8be9ff;
}

@media(max-width:768px){

    h1{
        font-size:3rem;
    }

    h2{
        font-size:1.4rem;
    }

    .informacoes p{
        font-size:1rem;
    }

}
</style>
