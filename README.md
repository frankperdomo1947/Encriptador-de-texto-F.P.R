<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/x-icon" href="./imagenes/favicon.ico">
    <link rel="stylesheet" href="./css/estilos.css">
    <title>Encriptador de Texto</title>
</head>
<body>

    <!-- Encabezado -->
    <header>
        <a href="#" rel="">
            <img src="./imagenes/logo.svg" alt="Logo Alura" class="logo">
        </a>    
    </header>

    <!-- Principal -->
    <main>
        <section class="encriptador">
            <textarea class="encriptar" placeholder="Ingrese el texto aquí"></textarea>
            <div class="encriptador-aviso">
                <img src="./imagenes/aviso.svg" alt="Imagen Aviso" class="img-aviso">
                <p class="texto-aviso">Solo letras minúsculas y sin acentos</p>
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
                <p class="texto-dos">Ingrese el texto que deseas encriptar o desencriptar</p>
           </div>
           <textarea type="mensaje" class="evaluar" readonly></textarea>
           <button type="submit" class="btn-copiar">Copiar</button>
         </section>  
    </main>

    <!-- Pie de Página -->
    <footer>
        <p class="copyright">&copy; copyright 2024 - Encriptador de Texto - desarrollado por FRANK PERDOMO</p>
        <a href="#" rel="">
            <img src="./imagenes/linkedin.svg" alt="Logo Linkedin" class="linked">
        </a>
        <a href="https://github.com/frankperdomo1947/Encriptador-de-texto-F.P.R" rel="">
            <img src="./imagenes/github.svg" alt="Logo Github" class="git">
        </a>
    </footer>

    <script src="./js/encriptador.js"></script>

</body>
</html>
