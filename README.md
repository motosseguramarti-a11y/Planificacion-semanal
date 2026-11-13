
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">



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

            border: 3px solid black;
            border-style: solid;
            border-radius: 15px;

            border-spacing: 5px;

            padding-top: 10px;
            padding-bottom: 10px;
            padding-left: 10px;
            padding-right: 10px;
        }

        th {
            background-color: #333333;
            color: white;

            border: 2px solid black;
            border-style: solid;
            border-radius: 10px;

            text-align: center;

            padding-top: 15px;
            padding-bottom: 15px;
            padding-left: 10px;
            padding-right: 10px;
        }

        td {
            border: 2px solid black;
            border-style: solid;
            border-radius: 10px;

            text-align: center;

            padding-top: 12px;
            padding-bottom: 12px;
            padding-left: 10px;
            padding-right: 10px;
        }

        /* Filas pares */
        tr:nth-child(even) {
            background-color: #D6EEEE;
        }

        /* Cambia de color al pasar el ratón */
        tr:hover {
            background-color: #D6EEEE;
        }

        .bloque {
            background-color: #333333;
            color: white;
            font-weight: bold;
        }

        .estudiar {
            background-color: #D6EEEE;
        }

        .clases {
            background-color: #1455ED;
        }

        .descansar {
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


        <!-- Siguiente dia -->
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
