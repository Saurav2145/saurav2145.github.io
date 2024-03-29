<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saurav Dutta - IISc Bangalore</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: left;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
        }
        .container {
            margin-top: 80px; /* Adjust according to header height */
            padding: 20px;
        }
        /* Dark theme */
        .dark-theme {
            background-color: #333;
            color: #fff;
        }
        /* Light theme */
        .light-theme {
            background-color: #fff;
            color: #333;
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>Saurav Dutta</h1>
        <h2>IISc Bangalore</h2>
        <button onclick="toggleTheme()">Toggle Theme</button>
    </header>
    <div class="container">
        <!-- Your content goes here -->
        <p>Welcome to my GitHub website!</p>
    </div>

    <script>
        function toggleTheme() {
            const body = document.body;
            body.classList.toggle('dark-theme');
            body.classList.toggle('light-theme');
        }
    </script>
</body>
</html>
