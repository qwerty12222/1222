<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Math Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
        }
        img {
            max-width: 300px;
            margin-bottom: 20px;
        }
        .input-container {
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <h1>Welcome to Image Math Example</h1>
    
    <!-- Display Image -->
    <img src="https://via.placeholder.com/300" alt="Math Image" id="image">
    
    <div class="input-container">
        <label for="num1">Number 1: </label>
        <input type="number" id="num1" placeholder="Enter a number">
    </div>
    
    <div class="input-container">
        <label for="num2">Number 2: </label>
        <input type="number" id="num2" placeholder="Enter another number">
    </div>
    
    <div class="input-container">
        <button onclick="performOperation()">Perform Addition</button>
    </div>

    <h2>Result: <span id="result">0</span></h2>

    <script>
        function performOperation() {
            // Get the values from the input fields
            var num1 = parseFloat(document.getElementById('num1').value);
            var num2 = parseFloat(document.getElementById('num2').value);

            // Check if the inputs are numbers
            if (!isNaN(num1) && !isNaN(num2)) {
                // Perform the addition
                var result = num1 + num2;
                // Display the result
                document.getElementById('result').innerText = result;
            } else {
                alert('Please enter valid numbers.');
            }
        }
    </script>
</body>
</html>
