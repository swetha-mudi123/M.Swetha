# M.Swetha
HTML CODE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stopwatch</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="stopwatch-container">
        <h1>Stopwatch</h1>
        <div id="display">00:00:00.000</div>
        <div class="buttons">
            <button id="start-stop">Start</button>
            <button id="reset">Reset</button>
            <button id="lap">Lap</button>
        </div>
        <div id="laps">
            <h2>Laps</h2>
            <ul id="lap-times"></ul>
        </div>
    </div>
    
    <script src="script.js"></script>
</body>
</html>
