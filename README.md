# FRONTEND-WEB-DEVELOPMET

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Quiz Application</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f7f7f7;
        }
        .quiz-container {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .quiz-question {
            font-size: 1.2em;
            margin-bottom: 10px;
        }
        .quiz-options {
            list-style-type: none;
            padding: 0;
        }
        .quiz-options li {
            margin-bottom: 10px;
        }
        .feedback {
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="quiz-container">
        <div id="question" class="quiz-question"></div>
        <ul id="options" class="quiz-options"></ul>
        <div id="feedback" class="feedback"></div>
    </div>
    <script src="quiz.js"></script>
</body>
</html>

