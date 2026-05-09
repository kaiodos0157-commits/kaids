<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RioTH</title>

<style>

body{
    margin:0;
    padding:0;
    background:#0f0f0f;
    font-family:Arial;
    color:white;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.container{
    text-align:center;
}

h1{
    font-size:80px;
    color:#00aeff;
    text-shadow:0 0 20px #00aeff;
}

p{
    font-size:20px;
    color:#aaa;
}

button{
    margin-top:20px;
    padding:15px 40px;
    border:none;
    border-radius:12px;
    background:#00aeff;
    color:white;
    font-size:20px;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    transform:scale(1.05);
    box-shadow:0 0 20px #00aeff;
}

</style>
</head>
<body>

<div class="container">
    <h1>RioTH</h1>
    <p>O futuro das apostas.</p>

    <button onclick="jogar()">
        Jogar
    </button>
</div>

<script>

function jogar(){
    alert("Sistema iniciando...");
}

</script>

</body>
</html>
