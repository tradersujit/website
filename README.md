<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome from Sujit</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('https://png.pngtree.com/thumb_back/fw800/background/20230411/pngtree-the-background-scene-of-the-game-is-dazzling-image_2382309.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
        }
        body::after {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.4);
            z-index: -1;
        }
        header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            color: white;
        }
        .logo {
            max-width: 100px;
            height: auto;
            border-radius: 10px;
        }
        .header-text {
            text-align: center;
            flex-grow: 1;
        }
        .header-text h1 {
            font-size: 3rem;
            margin: 0;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }
        .header-text .sub-heading {
            font-size: 1.5rem;
            color: #ff7e5f;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
        }
        nav {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-evenly;
            gap: 10px;
            margin-top: 15px;
        }
        nav a {
            text-decoration: none;
        }
        nav button {
            background: #ff7e5f;
            color: #fff;
            border: none;
            padding: 10px 20px;
            font-size: 1rem;
            border-radius: 5px;
            cursor: pointer;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s, background 0.3s;
            width: 100%;
            max-width: 180px;
        }
        nav button:hover {
            transform: scale(1.1);
            background: #ff543e;
        }
        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
            gap: 20px;
            margin: 20px auto;
            padding: 0 15px;
        }
        .content img {
            width: 90%;
            max-width: 300px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s;
        }
        .content img:hover {
            transform: scale(1.05);
        }
        .editing-info {
            text-align: center;
            margin-top: 20px;
            padding: 15px;
            background: rgba(0, 0, 0, 0.6);
            border-radius: 10px;
        }
        .editing-info h2 {
            color: #ff7e5f;
        }
        @media (max-width: 768px) {
            .header-text h1 {
                font-size: 2.5rem;
            }
            .header-text .sub-heading {
                font-size: 1.2rem;
            }
            nav button {
                font-size: 0.9rem;
                padding: 8px 15px;
            }
            .content img {
                max-width: 90%;
            }
        }
    </style>
</head>
<body>
    <header>  
        <img src="https://i.imgur.com/3mtrZiy.jpeg" alt="Logo" class="logo">  
        <div class="header-text">
            <h1>Welcome</h1>
            <div class="sub-heading">Sujit</div>
        </div>
    </header>
    <nav>
        <a href="https://tradersujit.github.io/trader/image.html">
            <button>Trading</button>
        </a>                                
        </a>  
        <a href="C:\Users\91790\Desktop\Website\web design.html">
            <button>Web Development</button>
        </a>  
        <a href="C:\Users\91790\Desktop\Website\video editng.html" target="_blank">
            <button>Video Editing</button>
        </a>        
    </nav>
    <div class="content">
        <img src="https://i.imgur.com/H5KI1mV.jpeg" alt="Image 1">
        <img src="https://i.imgur.com/3DeAhg2.jpeg" alt="Image 2">
    </div>
</body>
</html>
