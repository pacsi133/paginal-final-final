
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KIARA - Ropa</title>
    <style>
        /* Estilos modificados */

        body {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            height: 100vh;
            margin: 0;
        }

        header {
            background-color: green; /* Cambio de color a verde */
            font-size: 36px; /* Tamaño del título más grande */
            margin-bottom: 20px; /* Espacio añadido abajo del título */
        }

        #buscador {
            position: absolute;
            top: 10px;
            right: 10px;
            display: flex;
            align-items: center;
        }

        #cuadro-busqueda {
            padding: 5px;
            border: 1px solid #333;
            border-radius: 5px;
            margin-right: 5px;
        }

        #lupa {
            width: 20px;
            height: 20px;
            cursor: pointer;
        }

        section {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
        }

        .producto {
            width: 240px;
            height: 240px;
            margin: 20px;
            display: inline-block;
            vertical-align: top;
            transition: transform 0.3s ease;
        }

        .producto img {
            width: 100%;
            height: 100%;
        }

        .producto:hover {
            transform: scale(1.2);
        }

        .texto-precio {
            text-align: center;
            margin-top: 10px;
            font-family: 'Arial', sans-serif;
            font-size: 16px;
            color: #333;
        }

        .ofertas-especiales {
            background-color: black; /* Fondo negro */
            color: white; /* Texto blanco */
            padding: 20px;
            font-family: 'Arial', sans-serif;
            font-size: 18px;
            line-height: 1.5;
            width: 100%;
            box-sizing: border-box;
            margin-top: 20px; /* Espacio añadido arriba de las ofertas especiales */
            margin-bottom: 20px; /* Espacio añadido abajo de las ofertas especiales */
        }

        .terminos-condiciones {
            background-color: black; /* Fondo negro */
            color: white; /* Texto blanco */
            padding: 20px;
            font-family: 'Arial', sans-serif;
            font-size: 18px;
            line-height: 1.5;
            width: 100%;
            box-sizing: border-box;
            margin-top: 20px; /* Espacio añadido arriba de los términos y condiciones */
            margin-bottom: 20px; /* Espacio añadido abajo de las ofertas especiales */
        }
    </style>
</head>
<body>

    <header>
        KIRA
    </header>

    <div id="buscador">
        <input type="text" id="cuadro-busqueda" placeholder="Buscar...">
        <img id="lupa" src="https://imgur.com/lupa_icono.png" alt="Icono de lupa">
    </div>

    <section class="ofertas-especiales">
        Aprovecha estos descuentos por Navidad, ¡son una locura!
    </section>

    <section>
        <h2>Ofertas Especiales</h2>

        <div class="producto">
            <p> <a href="camisa blanca.html"><img src="https://i.pinimg.com/564x/dc/5f/20/dc5f2084010df0f3a7bbb0c2482fc937.jpg" alt="Polo de lana azul"></a>
            <div class="texto-precio">
                <p>Polo de lana azul</p>
                <p>Precio: S/ 99</p>
            </div>
        </div>

        <div class="producto">
             <p> <a href="camisa blanca.html"><img src="https://i.pinimg.com/564x/4b/c9/25/4bc925416679069ac649658b5184c16d.jpg"  alt="Polo blanco bonito"></a>
            <div class="texto-precio">
                <p>Camisa blanca</p>
                <p>Precio: S/ 79</p>
            </div>
        </div>

        <!-- Imágenes restauradas -->
        <div class="producto">
           <p> <a href=""> <img src="https://i.pinimg.com/564x/27/58/61/27586140fcdaaed1c759cb9551da984e.jpg" alt="Polo rojo elegante"></a>
            <div class="texto-precio">
                <p>Polo rojo elegante</p>
                <p>Precio: S/ 89</p>
            </div>
        </div>

</body>

</html>
