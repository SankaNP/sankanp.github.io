<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Website</title>
    <style>
        /* Body and Background Color */
        body {
            background-color: #f0f8ff;  /* Light blue background */
            font-family: 'Arial', sans-serif;
            text-align: center;
            color: #333;
        }

        /* Styling for the Heading */
        h1 {
            color: #4CAF50;  /* Green color */
            font-size: 48px;
            margin-top: 50px;
        }

        /* Styling for the Image */
        .my-image {
            width: 400px;
            height: auto;
            border-radius: 10px;
            margin-top: 30px;
        }

        /* Styling for the Link */
        a {
            color: #ff6347;  /* Tomato color */
            font-size: 18px;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Button Styling */
        button {
            padding: 10px 20px;
            font-size: 18px;
            background-color: #ff6347;  /* Tomato color */
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 30px;
        }

        button:hover {
            background-color: #ff4500;  /* Darker tomato color */
        }
    </style>
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
