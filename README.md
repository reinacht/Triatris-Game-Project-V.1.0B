<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Triatris Game README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e1e;
            color: white;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #ff69b4; /* Pink */
        }
        h2 {
            color: #00ffff; /* Cyan */
        }
        p {
            font-size: 16px;
            line-height: 1.5;
        }
        .red { color: #ff4d4d; }
        .green { color: #4dff4d; }
        .blue { color: #4d4dff; }
        .yellow { color: #ffff4d; }
        .orange { color: #ffb84d; }
        .purple { color: #b84dff; }
        .rainbow {
            background: linear-gradient(to right, red, orange, yellow, green, blue, indigo, violet);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        ul {
            margin-left: 20px;
        }
    </style>
</head>
<body>
    <h1 class="rainbow">Triatris Game for Project UAS</h1>

    <h2>Game Mechanism :</h2>
    <ul>
        <li class="green">Shape only merged once, so if shape collision, they will be merged</li>
        <li class="yellow">There is ghost shape in hard difficulty</li>
        <li class="red">Warning: epilepsy</li>
        <li class="blue">Have fun!</li>
    </ul>

    <h2>Instructions :</h2>
    <p>If you wanna re-build, please read <span class="purple">command.txt</span> in <span class="orange">File Source Code</span>. I'm too lazy to explain.</p>

    <p><span class="red">File Exe:</span> You can just download .exe file then run in your computer. You also can remove all file except <span class="yellow">Triatris.exe</span> in this folder.</p>

    <p><span class="blue">File Source Code:</span> Main resource if you wanna rebuild.</p>
</body>
</html>
