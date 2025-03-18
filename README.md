<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Title and Heading -->
    <h1>Welcome to My Personal Website!</h1>

    <!-- Image -->
    <img src="https://via.placeholder.com/400" alt="Sample Image" class="my-image"/>

    <!-- Hyperlink -->
    <p>Check out this cool website for more information:</p>
    <a href="https://www.example.com" target="_blank">Visit Example.com!</a>

    <!-- Button with OnClick event -->
    <br><br>
    <button onclick="showMessage()">Click Me for a Surprise!</button>

    <!-- JavaScript Function -->
    <script>
        function showMessage() {
            alert("Surprise! You clicked the button!");
        }
    </script>

</body>
</html>
