<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú Desplegable</title>
    <style>
        /* Estilos del menú */
        .menu {
            list-style: none;
            padding: 0;
        }

        .menu-item {
            display: inline-block;
            margin-right: 20px;
            position: relative;
        }

        .submenu {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            background-color: #fff;
            padding: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        /* Estilos para mostrar el submenú al hacer clic */
        .menu-item:hover .submenu {
            display: block;
        }
    </style>
</head>
<body>
    <ul class="menu">
        <li class="menu-item">Inicio
            <ul class="submenu">
                <li><a href="#">Subpágina 1</a></li>
                <li><a href="#">Subpágina 2</a></li>
                <li><a href="#">Subpágina 3</a></li>
            </ul>
        </li>
        <li class="menu-item">Acerca de
            <ul class="submenu">
                <li><a href="#">Equipo</a></li>
                <li><a href="#">Historia</a></li>
            </ul>
        </li>
        <li class="menu-item">Servicios
            <ul class="submenu">
                <li><a href="#">Servicio 1</a></li>
                <li><a href="#">Servicio 2</a></li>
                <li><a href="#">Servicio 3</a></li>
            </ul>
        </li>
        <li class="menu-item">Contacto
            <ul class="submenu">
                <li><a href="#">Información de contacto</a></li>
                <li><a href="#">Ubicación</a></li>
            </ul>
        </li>
    </ul>
</body>
</html>
