<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Die professionelle Webseite von Dr. Shakhriiar Gurbanzade, einem erfahrenen Augenarzt in Kolbermoor, Bayern, Deutschland.">
    <title>Dr. Shakhriiar Gurbanzade | Augenarzt</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('https://cdn.pixabay.com/photo/2017/08/26/15/37/eye-2683414_1280.jpg'); 
            background-size: cover;
            background-position: center;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgba(51, 51, 51, 0.8); /* Полупрозрачный фон для текста в хедере */
            color: #fff;
            padding: 15px; /* Уменьшенный отступ сверху и снизу */
            text-align: center;
            animation: fadeInHeader 3s ease-in-out;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        h1 {
            font-size: 1.5em; /* Уменьшенный размер имени */
            font-weight: bold;
            color: #fff;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
            margin-left: 15px; /* Отступ между фотографией и именем */
            animation: zoomIn 2s ease-in-out forwards;
        }
        .profile-pic {
            border-radius: 50%;
            width: 100px; /* Уменьшенный размер фотографии */
            height: 100px;
            display: block;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }
        @keyframes zoomIn {
            0% {
                opacity: 0;
                transform: scale(0.5);
            }
            100% {
                opacity: 1;
                transform: scale(1);
            }
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 15px; /* Уменьшенные отступы */
            background-color: rgba(128, 128, 128, 0.8);
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            animation: fadeIn 2s ease-in-out;
        }
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
        h2 {
            color: #333;
        }
        .bio, .specializations, .contact {
            margin-bottom: 15px; /* Уменьшенный отступ между секциями */
        }
        .bio ul {
            list-style: none;
            padding: 0;
        }
        .bio ul li {
            margin-bottom: 10px; /* Уменьшенный отступ между пунктами */
            padding-left: 20px;
            position: relative;
            font-size: 1.1em;
            opacity: 0;
            animation: slideIn 3s ease-in-out forwards;
        }
        .bio ul li:before {
            display: none; /* Убраны точки перед пунктами */
        }
        .bio ul li:nth-child(1) {
            animation-delay: 0.5s;
        }
        .bio ul li:nth-child(2) {
            animation-delay: 1s;
        }
        .bio ul li:nth-child(3) {
            animation-delay: 1.5s;
        }
        .bio ul li:nth-child(4) {
            animation-delay: 2s;
        }
        @keyframes slideIn {
            0% {
                opacity: 0;
                transform: translateX(-50px);
            }
            100% {
                opacity: 1;
                transform: translateX(0);
            }
        }
        .contact a {
            color: #ffffff;
            font-weight: bold;
            text-decoration: underline;
        }
        footer {
            background-color: rgba(51, 51, 51, 0.8);
            color: #fff;
            text-align: center;
            padding: 10px;
            font-size: 0.8em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <!-- Фотография слева от имени -->
        <img src="https://media.licdn.com/dms/image/v2/D4E03AQGYhLeZAlBHmw/profile-displayphoto-shrink_800_800/profile-displayphoto-shrink_800_800/0/1714934868934?e=1731542400&v=beta&t=0Xr38DC364RJQoD-33lqtlOG_CnUzAZwNCdL_YPQ_NM" alt="Dr. Shakhriiar Gurbanzade" class="profile-pic">
        <h1>Dr. Shakhriiar Gurbanzade</h1>
    </header>

    <div class="container">
        <section class="bio">
            <h2>Über mich</h2>
            <ul>
                <li>Mein Name ist Shakhriiar Gurbanzade und ich arbeite in Kolbermoor, Bayern, Deutschland</li>
                <li>Ich wurde in Baku, Aserbaidschan geboren und habe 2015 die Medizinische Universität in der Stadt Samara, Russland, abgeschlossen</li>
                <li>Im Jahr 2020 bin ich als Facharzt für Augenheilkunde nach Deutschland umgezogen. Seitdem arbeite ich in Bayern, und seit 2022 bin ich in der Chiemsee Augentagesklinik tätig</li>
            </ul>
        </section>

        <section class="specializations">
            <h2>Schwerpunkte</h2>
            <ul>
                <li>Konservative Behandlung eines breiten Spektrums an Augenerkrankungen</li>
                <li>Refraktive und Excimer Laser Chirurgie</li>
            </ul>
        </section>

        <section class="contact">
            <h2>Kontakt</h2>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/shakhriiar-gurbanzade-38a937240?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank">Dr. Gurbanzade auf LinkedIn</a></p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Dr. Shakhriiar Gurbanzade. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>

