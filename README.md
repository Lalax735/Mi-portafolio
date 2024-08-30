<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio Personal</title>
    <link rel="stylesheet" href="syless.css">

</head>
<body>
    <header>
        <h1>Laura Vanegas</h1>
        <p>Me apasiona el futbol y el baile.</p>
        <h2>Mi lema personal es:</h2>
        <p> "Nunca dejar de seguir avanzando"</p>
    </header>
    <section>
        <figure>
            <img src="C:\Users\mbalb\Downloads\m.jpg" alt="Prog" width="300" height="200" >
        </figure>
        <img src="C:\Users\mbalb\Downloads\descarga.jpeg" alt="Red" width="400" height="300" >
        <figcaption>Arte y Cultura </figcaption>
    </section>

    <nav>
        <ul>
            <li><a href="https://atlnacional.com.co/quienes-somos/" target="_blank">Ejemplo 1</a></li> 
            <li><a href="https://www.google.com/intl/es-419/gmail/about/" target="_blank">Ejemplo 2</a></li>
            <li><a href="https://cdigital.cun.edu.co/X" target="_blank">Ejemplo 3</a></li>
            <li>
                <ul>
                    <li><a href="https://www.youtube.com/?app=desktop&hl=es&themeRefresh=1" target="_blank">Ejemplo 4</a></li>
                    <li><a href="https://www.google.com/?hl=es" target="_blank">Ejemplo 5</a></li>
                </ul>
            </li>
        </ul>
            
    </nav>
    <section>
        <form action="#" method="post">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>

            <label for="Email">Correo Electronico</label>
            <input type="email" id="name" name="name" required>

            <label for="coments">Comentarios</label>
            <textarea id="coments" name="coments" rows="4" required></textarea>

            <label for="reason">Otras:</label>
            <select id="reason" name="reason">
                <option value="Consulta">Consulta</option>
                <option value="Comentario">Comentario</option>
                <option value="Otros">Otros</option>
            </select>

            <label>
                <input type="checkbox" name="terms" id="terms" required>
                Acepto los terminos y condiciones
            </label>
            <button type="submit">Enviar</button>

        </form>
    </section>
</form>

</body>
</html>
