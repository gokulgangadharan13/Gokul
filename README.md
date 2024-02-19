<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gokul Gangadharan</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-image: url('https://images.pexels.com/photos/255379/pexels-photo-255379.jpeg?cs=srgb&dl=pexels-miguel-%C3%A1-padri%C3%B1%C3%A1n-255379.jpg&fm=jpg&_gl=1*p2vc3p*_ga*MTI1ODg0NDkxMC4xNzA4MzIzODUx*_ga_8JE65Q40S6*MTcwODMyMzg1MS4xLjEuMTcwODMyMzg1My4wLjAuMA..');
            background-size: cover;
            color: white;
            text-align: center;
            font-size: 20px;
            font-weight: bold;
        }
        .container {
            padding: 20px;
            border: 2px solid black;
            display: inline-block;
        }
        a {
            color: white; /* Default link color */
            text-decoration: none; /* Remove underline */
        }
        a.linkedin {
            color: blue; /* LinkedIn link color */
        }
        form {
            border: 2px solid black;
            padding: 20px;
            display: inline-block;
            margin-top: 20px;
        }
        input[type="text"],
        input[type="tel"],
        input[type="email"],
        input[type="submit"] {
            padding: 10px;
            margin-bottom: 10px;
            border: 2px solid black;
            border-radius: 5px;
            width: 100%;
            background-color: #333; /* Dark background color */
            color: white; /* Text color */
        }
        label {
            font-size: 20px;
            display: block;
            margin-bottom: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 style="font-size: 36px;">Gokul Gangadharan</h1>
        <p>
            👋 Hi, I’m Gokul Gangadharan<br>
            👀 I’m interested in Tech, Gadgets, and Space science<br>
            🌱 I’m learning Data Analytics at Durham College<br>
            📈 I'm currently looking for Co-op opportunities in Data Analytics | BI | Supply Chain | Shipping<br>
            📫 How to reach me: <a href="https://linkedin.com/in/gokul-gangadharan-gg13" class="linkedin">LinkedIn</a><br>
            📞 Cell: 4377997153<br>
            📧 Email: gokulgangadharan13@gmail.com<br>
            🏠 Address: 1973 Secretariat Place, Oshawa, ON, L1L1C7
        </p>
    </div>

    <h1>Contact Me</h1>
    <form action="submit.php" method="POST">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name"><br>
        <label for="organization">Organization:</label><br>
        <input type="text" id="organization" name="organization"><br>
        <label for="phone">Phone Number:</label><br>
        <input type="tel" id="phone" name="phone"><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br><br>
        <input type="submit" value="Submit">
    </form>
</body>
</html>
