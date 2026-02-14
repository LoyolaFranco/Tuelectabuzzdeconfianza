<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tu electabuzz de confianza</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#111;
    color:white;
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:center;
    height:100vh;
    text-align:center;
}

.logo{
    margin-bottom:40px;
}

.logo img{
    width:180px;
    border-radius:50%;
}

.card{
    width:85%;
    max-width:400px;
    padding:25px;
    margin:15px 0;
    border-radius:20px;
    text-decoration:none;
    color:white;
    font-size:1.5em;
    font-weight:bold;
    display:block;
}

.electricidad{
    background:#FFD000;
    color:black;
}

.camaras{
    background:#8B0000;
}

.card:hover{
    transform:scale(1.03);
    transition:0.2s;
}
</style>
</head>

<body>

<div class="logo">
<img src="logo.jpg" alt="Tu electabuzz de confianza">
</div>

<a href="electricidad.html" class="card electricidad">
⚡ ELECTRICIDAD
</a>

<a href="camaras.html" class="card camaras">
📷 CÁMARAS DE SEGURIDAD
</a>

</body>
</html>
