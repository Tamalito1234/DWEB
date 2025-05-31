<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Inicio - Dashboard</title>
     <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: rgb(255, 149, 0);
            margin: 0;
            padding: 0;
            display: flex;
        }

        /* Estilos para el menú lateral */
        .sidebar {
            width: 200px; /* ancho del menú */
            background-color: blue;
            color: white;
            height: 100vh; /* altura completa de la ventana */
            padding: 20px;
            position: fixed; /* mantener fijo al hacer scroll */
        }

        .sidebar h2 {
            margin-top: 0; /* eliminar el margen superior */
            text-align: center;
        }

        .sidebar ul {
            list-style: none; /* eliminar los puntos de la lista */
            padding: 0;
        }

        .sidebar ul li {
            padding: 10px;
            margin-bottom: 10px;
            background-color: darkblue;
            border-radius: 5px;
        }

        .sidebar ul li:hover {
            background-color: aqua; /* color al pasar el mouse */
            cursor: pointer; /* cambiar a cursor de mano */
            color: black;
        }

        .sidebar ul li a {
            color: white;
            text-decoration: none;
            display: block;
        }

        .sidebar ul li:hover a {
            color: black;
        }

        /* Contenedor principal del contenido a la derecha */
        .main-content {
            margin-left: 220px; /* desplazar el contenido a la derecha */
            padding: 20px;
            width: 100%; /* ocupar el ancho disponible */
        
        }

        h1 {
            text-align: center;
            color: rgb(0, 0, 128);
            text-shadow: 2px 3px white;
            font-size: 40px;
        }

        .dashboard {
            display: grid; /* organizar los cards */
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); /* ajustar columnas */
            gap: 20px; /* espacio entre tarjetas */
            margin-top: 30px;
        }

        .card {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
            box-shadow: 0 2px 2px;
    
        }

        .card h2 {
            margin-bottom: 10px;
            color: darkblue;
        }
        .cardbcp {
            background-color: white;
            padding: 10px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
            margin-top: 200px;

        }
        
    </style>
</head>
<body>
    <div class="sidebar">
        <h2>Menú de Opciones</h2>
        <ul>
            <li><a href="index.html">Inicio</a></li>
            <li><a href="resumen.html">Resumen</a></li>
            <li><a href="prestamos.html">Préstamos</a></li>
            <li><a href="contacto.html">Contacto</a></li>
        </ul>
        
        <div class="cardbcp">
        <img src=bcp.png alt="bcplogo" width="180px">
        </div>
   </div>

    <div class="main-content">
        <section id="inicio">
            <h1>Dashboard Financiero - Préstamos Bancarios</h1>
           <div class="dashboard">
    <!-- Primer grupo de cards -->
    <div class="card">
        <h2>Cuota Inicial</h2>
        <p>S/ 32,550</p>
    </div>
    <div class="card">
        <h2>Monto Financiero</h2>
        <p>S/ 122,450</p>
    </div>
    <div class="card">
        <h2>Interés Total</h2>
        <p>S/ 3,302.470</p>
    </div>
</div>

<div class="dashboard">
    <!-- Segundo grupo de cards debajo -->
    <div class="card">
        <h2>Seguro</h2>
        <p>S/ 1,250</p>
    </div>
    <div class="card">
        <h2>Comisiones</h2>
        <p>S/ 780</p>
    </div>
    <div class="card">
        <h2>Cuota Mensual</h2>
        <p>S/ 1,250</p>
    </div>
</div>
<div class="dashboard">
                <div class="card">
                    <h2>Total a Pagar</h2>
                    <p>S/ 158,032.47</p>
                </div>
                <div class="card">
                    <h2>Fecha de Desembolso</h2>
                    <p>15/05/2024</p>
                </div>
                <div class="card">
                    <h2>Fecha de Vencimiento</h2>
                    <p>15/05/2044</p>
                </div>
                <div class="card">
                    <h2>Tipo de Préstamo</h2>
                    <p>Hipotecario</p>
                </div>
            </div>

        </section>
    </div>
</body>
</html>
