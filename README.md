<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/x-icon" href="./imagenes/favicon.ico">
    <link rel="stylesheet" href="./imagenes/CSS/Estilos.css">
    <title>encriptador de texto</title>
</head>
<body>
    <!-- Encabezado -->
    <header>
        <a href="#" rel="">
            <img src="./imagenes/logo.svg" alt="logo alura" class="logo">
        </a>
    </header>
<!-- Principal -->
 <main>
    <section class="encriptador">
        <textarea class="encriptador" placeholder="ingrese el texto aqui"></textarea>
        <div class="encriptador-aviso">
            <img src="./imagenes/aviso.svg" alt="Imagen aviso" class="img-aviso">
            <p class="texto-aviso">solo letras minusculas y sin acentos</p>
        </div>
        <div class="encriptador-contenedor">
            <button type="submit" class="btn-encriptar">Encriptar!</button>
            <button type="submit" class="btn-desencriptar">Desencriptar!</button>
        </div>
    </section>
    <section class="tarjeta">
        <div class="tarjeta-contenedor">
            <img src="./imagenes/muñeco.svg" alt="Imagen Muñeco" class="img-muñeco">
            <p class="texto-uno">Ningún mensaje fue encontrado</p>
            <p class="texto-dos">Ingerese el texto que deseas encriptar o desencriptar</p>
        </div>
        <textarea type="mensaje" class="evaluar" readonly></textarea>
        <button type="submit" class="btn-copiar">Copiar</button>
    </section>
 </main>
<!-- Pie de pagina -->

<footer>
    <p class="copyright">&copy; Copyright 2023 - Encriptador de Texto - Desarrollado por Leonardo Cruz</p>
    <a href="#" rel="">
        <img src="./imagenes/linkedin.svg" alt="logo Linkedin" class="linkedin">
    </a>
    <a href="#" rel="">
        <img src="./imagenes/github.svg" alt="logo Github" class="Git">
    </a>
</footer>

</body>
</html>
