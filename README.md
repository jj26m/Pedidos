<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pedidos Aurex Energy - Aurex Corporation</title>
    <style>
        body {
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        #header {
            background-color: red;
            padding: 10px;
            font-size: 2em;
            color: black;
        }
        .form-container {
            margin-top: 20px;
        }
        .input-box {
            margin: 10px;
            padding: 10px;
            font-size: 1.2em;
            width: 250px;
        }
        .submit-btn {
            padding: 10px;
            font-size: 1.2em;
            background-color: blue;
            color: white;
            border: none;
            cursor: pointer;
        }
        .submit-btn:hover {
            background-color: darkblue;
        }
    </style>
</head>
<body>

    <div id="header">Aurex Corporation - Pedidos Aurex Energy</div>
    <div class="form-container">
        <h2>Formulario para Pedir Aurex Energy</h2>
        <form id="formularioPedido">
            <input type="text" id="nombreIC" class="input-box" placeholder="Nombre IC" required><br>
            <input type="text" id="domicilioIC" class="input-box" placeholder="Domicilio IC" required><br>
            <select id="sabor" class="input-box" required>
                <option value="Tropical Mango (Original)">Tropical Mango (Original
