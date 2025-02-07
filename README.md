
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>
        condo Game Rules</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #d32f2f;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        ol {
            margin: 20px 0;
        }
        li {
            margin: 10px 0;
        }
        .form-container {
            margin-top: 20px;
            text-align: center;
        }
        input[type="text"] {
            padding: 10px;
            font-size: 16px;
            width: 80%;
            max-width: 400px;
            margin-top: 10px;
            border-radius: 4px;
            border: 1px solid #ccc;
        }
        button {
            padding: 10px 15px;
            background-color: #d32f2f;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #c62828;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Squid Game Rules</h1>

        <ol>
            <li>All participants must play to win.</li>
            <li>The games are brutal, and there are no second chances.</li>
            <li>Only the last person remaining will win the prize.</li>
            <li>Players will compete in a series of deadly children's games.</li>
            <li>All rules of the game must be followed; failure to do so results in immediate disqualification.</li>
            <li>Teamwork is possible, but in the end, it is every player for themselves.</li>
            <li>Players are strictly prohibited from leaving the game once they enter.</li>
            <li>The prize money grows as players are eliminated, but so does the danger.</li>
            <li>There are no escapes, and the consequences of losing are severe.</li>
        </ol>

        <div class="form-container">
            <label for="name">Enter your name to join the game:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name here" required>
            <br><br>
            <button onclick="submitName()">Join condo Game</button>
        </div>
    </div>

    <script>
        function submitName() {
            const name = document.getElementById("name").value;
            if (name) {
                alert(name + ", you have joined the Squid Game!");
            } else {
                alert("Please enter your name before joining.");
            }
        }
    </script>

</body>
</html>
