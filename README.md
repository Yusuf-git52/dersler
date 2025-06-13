# dersler
{
  "scripts": {
    "dev": "vite", // start dev server, aliases: `vite dev`, `vite serve`
    "build": "vite build", // build for production
    "preview": "vite preview" // locally preview production build
  }
}
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: url(img.jpg);
            background-size: cover;
        }

        .box {
            width: 450px;
            background: lightblue;
            padding: 40px;
            text-align: center;
            margin: auto;
            margin-top: 5%;
            color: #fff;
            font-family: sans-serif;
        }

        .box img {
            border-radius: 50%;
            width: 200px;
            height: 200px;
            transition: 0.5s;
            cursor: pointer;
            background-size: 100% 100%;
        }

        .box img:hover {
            transform: scale(0.9);
        }

        .box h1 {
            font-size: 40px;
            letter-spacing: 4px;
            font-weight: 100;
        }

        .box h5 {
            font-size: 20px;
            font-weight: 100;
            letter-spacing: 3px;
        }

        .box p {
            text-align: justify;
        }

        ul {
            margin: 0;
            padding: 0;
        }

        .box li {
            display: inline-block;
            margin: 6px;
            list-style: none;
        }

        .box li a {
            color: white;
            font-size: 60px;
            transition: all ease-in-out 250ms;
        }

        .box li a:hover {
            color: #b9b9b9;
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"
        integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>
    <div class="box">
        <img src="profile.png">
        <h1>Yusuf Güler</h1>

        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Officiis reprehenderit vel tempore dicta?
            Temporibus officiis atque ullam tenetur iste eveniet accusantium sint optio eaque, sed quisquam magnam sunt
            quae rem.</p>
        <li><a href="#"><i class="fab fa-facebook"></i></a></li>
        <li><a href="#"><i class="fab fa-x"></i></a></li>
        <li><a href="#"><i class="fab fa-instagram"></i></a></li>

    </div>
</body>

</html>
