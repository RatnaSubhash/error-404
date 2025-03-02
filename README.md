<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Error 404 - Page Not Found</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: url('https://source.unsplash.com/1600x900/?college,funny,meme') no-repeat center center/cover;
            text-align: center;
            color: rgb(0, 0, 0);
        }
        h1 {
            font-size: 6rem;
            color: #ffcc00;
            font-weight: 700;
            text-shadow: 3px 3px 8px rgba(0, 0, 0, 0.7);
        }
        p {
            font-size: 1.5rem;
            font-weight: 400;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6);
        }
        a {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #ff5722;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: 700;
            box-shadow: 2px 2px 6px rgba(0, 0, 0, 0.5);
        }
        a:hover {
            background-color: #e64a19;
        }
        .funny-image {
            width: 250px;
            height: auto;
            margin-bottom: 20px;
        }
        @media (max-width: 600px) {
            h1 {
                font-size: 4rem;
            }
            p {
                font-size: 1.2rem;
            }
            .funny-image {
                width: 150px;
            }
        }
    </style>
</head>
<body>
    <img class="funny-image" src="https://i.imgur.com/O0DCcQy.png" alt="Funny Error Image">
    <h1>Oops! 404</h1>
    <p>Looks like your page got lost in cyberspace! 🚀</p>
    <a href="/">Back to Home</a>
</body>
</html>
