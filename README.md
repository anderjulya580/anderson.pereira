<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Perfil GitHub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
            text-align: center;
            padding: 20px;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background-color: #161b22;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(255, 255, 255, 0.1);
            animation: fadeIn 1.5s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .avatar {
            width: 150px;
            border-radius: 50%;
            border: 3px solid #58a6ff;
            animation: pulse 2s infinite alternate;
        }
        @keyframes pulse {
            from { transform: scale(1); }
            to { transform: scale(1.1); }
        }
        .name {
            font-size: 24px;
            font-weight: bold;
            margin-top: 10px;
            animation: slideIn 1.5s ease-in-out;
        }
        @keyframes slideIn {
            from { opacity: 0; transform: translateX(-50px); }
            to { opacity: 1; transform: translateX(0); }
        }
        .bio, .skills {
            font-size: 16px;
            margin: 10px 0;
            animation: fadeIn 2s ease-in-out;
        }
        .skills {
            font-size: 18px;
            font-weight: bold;
            color: #58a6ff;
        }
        .social {
            margin-top: 10px;
        }
        .social a {
            color: #58a6ff;
            text-decoration: none;
            margin: 0 10px;
            font-size: 18px;
            transition: transform 0.3s ease-in-out;
        }
        .social a:hover {
            transform: scale(1.2);
        }
    </style>
</head>
<body>
    <div class="container">
        <img class="avatar" src="https://github.com/SEU-USUARIO.png" alt="Avatar">
        <div class="name">Seu Nome</div>
        <div class="bio">Desenvolvedor Web apaixonado por código aberto e tecnologia.</div>
        <div class="skills">Especializado em React Native, Node.js, React, TypeScript e NestJS</div>
        <div class="social">
            <a href="https://github.com/SEU-USUARIO" target="_blank">GitHub</a>
            <a href="https://www.linkedin.com/in/anderson-pereira-61375a254/" target="_blank">LinkedIn</a>
        </div>
    </div>
</body>
</html>
