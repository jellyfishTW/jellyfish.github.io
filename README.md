# jellyfish.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>互動式網頁</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }
        .button-container {
            display: grid;
            gap: 10px;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            width: 80%;
            max-width: 400px;
        }
        .button {
            background-color: #007bff;
            color: white;
            padding: 15px;
            text-align: center;
            border-radius: 8px;
            text-decoration: none;
            font-size: 18px;
            transition: background-color 0.2s;
        }
        .button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>點擊下方按鈕前往不同的網址</h1>
    <div class="button-container">
        <a href="https://www.google.com" class="button" target="_blank">Google</a>
        <a href="https://www.bing.com" class="button" target="_blank">Bing</a>
        <a href="https://www.yahoo.com" class="button" target="_blank">Yahoo</a>
    </div>
</body>
</html>
