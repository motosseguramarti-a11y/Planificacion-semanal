<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Planificación semanal</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 30px;
        }

        h1 {
            text-align: center;
        }

        table {
            width: 100%;
            height: 300px;
            border: 2px solid black;
            border-radius: 15px;
            border-spacing: 5px;
            padding: 10px;
        }

        th, td {
            border: 1px solid black;
            border-radius: 10px;
            text-align: center;
            padding: 12px 10px;
        }

        th {
            background-color: #333333;
            color: white;
            padding: 15px 10px;
        }

        .bloque {
            background-color: #333333;
            color: white;
            font-weight: bold;
        }

        .estudiar {
            background-color: #DCEFEF;
        }

        .clases, .descansar {
            background-color: #1455ED;
        }
    </style>
</head>

<body>

    <h1>Planificacion semanal</h1>

    <table>
        <!-- Primera fila: dias -->
        <tr>
            <th>Bloques horarios</th>
            <th>Lunes</th>
            <th>Martes</th>
            <th>Miercoles</th>
            <th>Jueves</th>
            <th>Viernes</th>
            <th>Sabado</th>
            <th>Domingo</th>
        </tr>

        <!-- Mañana -->
        <tr>
            <td class="bloque">Manana</td>
            <td class="estudiar">Estudiar</td>
            <td class="estudiar">Estudiar</td>
            <td class="estudiar">Estudiar</td>
            <td class="estudiar">Estudiar</td>
            <td class="estudiar">Estudiar</td>

            <!-- rowspan ocupa manana y tarde -->
            <td class="estudiar" rowspan="2">
                Estudiar
            </td>

            <td class="descansar" rowspan="2">
                Descansar
            </td>
        </tr>

        <!-- Tarde -->
        <tr>
            <td class="bloque">Tarde</td>

            <!-- colspan ocupa de lunes a viernes -->
            <td class="clases" colspan="5">
                Clases IES Miralcamp - 1º DAW
            </td>
        </tr>
    </table>

</body>

</html>
