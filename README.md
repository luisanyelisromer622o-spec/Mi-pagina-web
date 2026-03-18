# Mi-pagina-web
C<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CV</title>

<style>
body{
    font-family: Arial;
    background:#eaeaea;
    padding:20px;
}

.cv{
    max-width:800px;
    margin:auto;
    background:white;
    padding:30px;
}

/* HEADER */
.top{
    display:flex;
    justify-content:space-between;
    align-items:center;
    margin-bottom:20px;
}

.foto{
    width:120px;
    height:140px;
    object-fit:cover;
    border:1px solid #ccc;
}

/* COLUMNAS */
.contenido{
    display:flex;
    gap:40px;
}

.col{
    flex:1;
}

/* TITULOS */
h2{
    border-bottom:2px solid black;
    padding-bottom:5px;
    margin-top:20px;
}

/* LISTAS */
ul{
    padding-left:20px;
}

li{
    margin-bottom:5px;
}
</style>

</head>

<body>

<div class="cv">

<!-- HEADER -->
<div class="top">
    <div>
        <h1>Luisanyelis González</h1>
        <p>Estudiante de Informática</p>
        <p>📞 04242645512</p>
        <p>📧 luisanyelisromer622o@gmail.com</p>
    </div>

    <img src="https://via.placeholder.com/120x140" class="foto">
</div>

<!-- CONTENIDO -->
<div class="contenido">

    <!-- IZQUIERDA -->
    <div class="col">

        <h2>💼 Experiencia Laboral</h2>

        <p><strong>Community Manager (Freelance)</strong></p>
        <p>2023 - Actualidad</p>
        <ul>
            <li>Gestión de redes sociales</li>
            <li>Creación de contenido</li>
            <li>Interacción con clientes</li>
        </ul>

        <p><strong>Asistente</strong></p>
        <p>2022 - 2023</p>
        <ul>
            <li>Organización de tareas</li>
            <li>Apoyo administrativo</li>
        </ul>

        <h2>💡 Habilidades</h2>
        <ul>
            <li>Creatividad</li>
            <li>Trabajo en equipo</li>
            <li>Aprendizaje rápido</li>
            <li>Manejo de redes sociales</li>
        </ul>

    </div>

    <!-- DERECHA -->
    <div class="col">

        <h2>🎓 Educación</h2>
        <p><strong>U.E.N "Dr Eduardo Rísquez"</strong></p>
        <p>Bachiller en proceso</p>

        <h2>🌎 Idiomas</h2>
        <ul>
            <li>Español (nativo)</li>
            <li>Inglés (básico)</li>
        </ul>

        <h2>🧠 Sobre mí</h2>
        <p>
        Estudiante de Informática con gran capacidad de aprendizaje, creatividad
        y motivación para crecer profesionalmente.
        </p>

    </div>

</div>

</div>

</body>
</html>
