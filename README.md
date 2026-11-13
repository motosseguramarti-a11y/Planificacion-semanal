<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Planificacion semanal</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 30px;
            background-color: white;
        }

        h1 {
            text-align: center;
            border-bottom: none !important;
            margin-bottom: 20px;
        }

        table {
            width: 100%;
            height: 300px;
            border: 2px solid black !important;
            border-radius: 15px;
            border-collapse: separate !important;
            border-spacing: 5px !important;
            padding: 10px !important;
            table-layout: auto !important;
        }

        th, td {
            border: 1px solid black !important;
            border-radius: 10px;
            text-align: center;
            padding: 12px 10px;
            width: 11.5%;
        }

        th:first-child, .bloque {
            width: 19.5%;
        }

        th {
            background-color: #333333 !important;
            color: white !important;
            padding: 15px 10px;
        }

        .bloque {
            background-color: #333333 !important;
            color: white !important;
            font-weight: bold;
        }

        .estudiar {
            background-color: #DCEFEF !important;
            color: black !important;
        }

        .clases, .descansar {
            background-color: #1455ED !important;
            color: black !important;
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
