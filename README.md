<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <title>誰是gay？</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            background-color: #f0f0f0;
        }
        h1 {
            color: #333;
            margin-bottom: 30px;
        }
        #answer {
            font-size: 24px;
            color: #ff4444;
            margin-top: 20px;
            display: none;
        }
        button {
            padding: 15px 30px;
            font-size: 18px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h1>誰是gay？</h1>
    <button onclick="showAnswer()">顯示答案</button>
    <div id="answer">林捷是gay</div>

    <script>
        function showAnswer() {
            document.getElementById('answer').style.display = 'block';
        }
    </script>
</body>
</html>
