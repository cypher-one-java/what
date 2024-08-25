<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Preguntas y Respuestas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #2c3e50;
            color: #ecf0f1;
            padding: 15px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .question-form, .answer-form {
            background: #fff;
            padding: 20px;
            margin: 20px 0;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .question-form textarea, .answer-form textarea {
            width: 100%;
            height: 100px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        .question-form button, .answer-form button {
            background-color: #3498db;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        .question-form button:hover, .answer-form button:hover {
            background-color: #2980b9;
        }
        .question, .answer {
            background: #fff;
            padding: 20px;
            margin: 10px 0;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .question h2, .answer h3 {
            margin-top: 0;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Preguntas y Respuestas</h1>
    </div>

    <div class="container">
        <!-- Formulario para hacer una pregunta -->
        <div class="question-form">
            <h2>Haz una pregunta</h2>
            <textarea placeholder="Escribe tu pregunta aquí..."></textarea>
            <button>Enviar Pregunta</button>
        </div>

        <!-- Formulario para responder una pregunta -->
        <div class="answer-form">
            <h2>Responde una pregunta</h2>
            <textarea placeholder="Escribe tu respuesta aquí..."></textarea>
            <button>Enviar Respuesta</button>
        </div>

        <!-- Sección de Preguntas y Respuestas -->
        <div class="question">
            <h2>¿Cuál es el mejor libro que has leído?</h2>
            <div class="answer">
                <h3>Respuesta 1:</h3>
                <p>El mejor libro que he leído es "1984" de George Orwell.</p>
            </div>
            <div class="answer">
                <h3>Respuesta 2:</h3>
                <p>Me parece que "Cien años de soledad" de Gabriel García Márquez es una obra maestra.</p>
            </div>
        </div>

        <!-- Puedes añadir más preguntas y respuestas aquí -->
    </div>
</body>
</html>
