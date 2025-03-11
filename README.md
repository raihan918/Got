# Got
This my first Repository 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Proposal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: pink;
            text-align: center;
            flex-direction: column;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        button {
            padding: 10px 20px;
            margin: 10px;
            border: none;
            cursor: pointer;
            font-size: 18px;
            border-radius: 5px;
        }
        #yesBtn {
            background-color: green;
            color: white;
        }
        #noBtn {
            background-color: red;
            color: white;
            position: absolute;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Will you be my Valentine? ❤️</h2>
        <button id="yesBtn">Yes</button>
        <button id="noBtn">No</button>
    </div>
    <script>
        document.getElementById("yesBtn").addEventListener("click", function() {
            alert("Yay! ❤️ I love you too!");
        });

        document.getElementById("noBtn").addEventListener("mouseover", function() {
            let x = Math.random() * window.innerWidth;
            let y = Math.random() * window.innerHeight;
            this.style.left = `${x}px`;
            this.style.top = `${y}px`;
        });
    </script>
</body>
</html>
