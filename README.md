<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>SetStock - Sistema de Gestión</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f6f8fa;
            color: #24292e;
            line-height: 1.6;
            padding: 40px;
            max-width: 900px;
            margin: auto;
        }

        h1 {
            color: #0366d6;
            border-bottom: 2px solid #eaecef;
            padding-bottom: 10px;
        }

        h2 {
            color: #24292e;
            margin-top: 40px;
            border-left: 5px solid #0366d6;
            padding-left: 10px;
        }

        ul {
            margin-left: 20px;
        }

        li {
            margin-bottom: 6px;
        }

        .box {
            background-color: #ffffff;
            border: 1px solid #e1e4e8;
            border-radius: 6px;
            padding: 20px;
            margin-top: 20px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }

        th, td {
            border: 1px solid #d0d7de;
            padding: 10px;
            text-align: center;
        }

        th {
            background-color: #f3f4f6;
        }

        footer {
            margin-top: 50px;
            font-size: 0.9em;
            text-align: center;
            color: #57606a;
        }
    </style>
</head>
<body>

    <h1>📦 SetStock</h1>
    <p><strong>Sistema de Gestión de Inventario</strong></p>

    <div class="box">
        <p>
            <strong>SetStock</strong> es una aplicación de escritorio diseñada para la gestión integral de un comercio,
            permitiendo controlar stock, ventas, compras, clientes, proveedores y usuarios de forma simple y ordenada.
        </p>
        <p>
            El sistema fue desarrollado como proyecto académico, pero con un enfoque práctico y real.
        </p>
    </div>

    <h2>🧾 Funcionalidades principales</h2>

    <div class="box">
        <h3>📦 Artículos</h3>
        <ul>
            <li>Alta, edición y eliminación de artículos</li>
            <li>Control de stock disponible</li>
            <li>Alertas de stock bajo</li>
            <li>Búsqueda por código o nombre</li>
        </ul>

        <h3>💰 Ventas</h3>
        <ul>
            <li>Registro de ventas</li>
            <li>Asignación opcional de clientes</li>
            <li>Descuentos y recargos</li>
            <li>Cálculo automático de totales</li>
            <li>Visualización gráfica</li>
            <li>Exportación de informes</li>
        </ul>

        <h3>🧾 Compras</h3>
        <ul>
            <li>Registro y edición de compras</li>
            <li>Asociación de proveedores</li>
            <li>Listado completo de compras</li>
            <li>Generación de informes en PDF</li>
        </ul>

        <h3>👥 Clientes y Proveedores</h3>
        <ul>
            <li>Gestión completa de clientes</li>
            <li>Gestión completa de proveedores</li>
            <li>Búsqueda por nombre, apellido o ID</li>
        </ul>
    </div>

    <h2>👤 Usuarios y Seguridad</h2>

    <div class="box">
        <ul>
            <li>Inicio de sesión con usuario y contraseña</li>
            <li>Sistema de roles (Administrador / Usuario)</li>
            <li>Restricción de funciones según el rol</li>
            <li>Gestión de usuarios</li>
            <li>Cierre de sesión sin cerrar la aplicación</li>
        </ul>

        <table>
            <tr>
                <th>Función</th>
                <th>Administrador</th>
                <th>Usuario</th>
            </tr>
            <tr>
                <td>Gestión de artículos</td>
                <td>✔️</td>
                <td>❌</td>
            </tr>
            <tr>
                <td>Ventas</td>
                <td>✔️</td>
                <td>✔️</td>
            </tr>
            <tr>
                <td>Compras</td>
                <td>✔️</td>
                <td>❌</td>
            </tr>
            <tr>
                <td>Usuarios</td>
                <td>✔️</td>
                <td>❌</td>
            </tr>
            <tr>
                <td>Exportar informes</td>
                <td>✔️</td>
                <td>❌</td>
            </tr>
        </table>
    </div>

    <h2>🗂️ Base de datos</h2>

    <div class="box">
        <ul>
            <li>Base de datos local incluida</li>
            <li>No requiere conexión a internet</li>
            <li>No requiere instalación de software adicional</li>
            <li>Información almacenada localmente</li>
        </ul>
    </div>

    <h2>🎓 Contexto del proyecto</h2>

    <div class="box">
        <p>
            SetStock fue desarrollado como proyecto académico / tesis,
            aplicando conceptos de programación, gestión de datos,
            control de usuarios y diseño de interfaces.
        </p>
    </div>

    <h2>📌 Estado del proyecto</h2>

    <div class="box">
        <p>🟢 <strong>Proyecto finalizado y funcional</strong></p>
    </div>

    <footer>
        <p><strong>Autor:</strong> Mati</p>
        <p>Sistema de Gestión de Inventario – SetStock</p>
    </footer>

</body>
</html>
