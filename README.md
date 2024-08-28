<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Supun Devendra - GitHub Profile</title>
    <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1c1e21;
            color: #dcdcdc;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        h1,
        h3 {
            margin: 0;
            padding: 0.5em;
            animation: fadeIn 2s;
        }

        h1 {
            color: #ff6347;
        }

        h3 {
            color: #ffa500;
        }

        .section {
            padding: 20px;
        }

        .stats-container {
            display: flex;
            justify-content: center;
            gap: 10px;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .stats-container img {
            border: 2px solid #333;
            border-radius: 10px;
            animation: fadeInUp 1s;
        }

        .social-links a {
            margin: 10px;
            text-decoration: none;
            transition: transform 0.2s;
        }

        .social-links a:hover {
            transform: scale(1.1);
        }

        .footer {
            margin-top: 20px;
            font-size: 0.9em;
            color: #777;
        }

        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(-20px);
            }

            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }

            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>Hey there! 😈 I'm Supun Devendra</h1>
        <h3>🚀 Driven Developer & Tech Enthusiast from Sri Lanka 🇱🇰</h3>
    </header>

    <section class="section">
        <h2>👨‍🎓 About Me</h2>
        <ul style="list-style: none; padding: 0;">
            <li>🎓 Currently pursuing a degree at the <b>University of Westminster</b></li>
            <li>🌐 Deeply engaged in mastering <b>Python, Java, and cutting-edge technologies</b></li>
            <li>🗣️ Open to discussing <b>Web Development, Java, and Python</b> — let's connect!</li>
        </ul>
    </section>

    <section class="section">
        <h2>📊 GitHub Stats</h2>
        <div class="stats-container">
            <img src="https://github-readme-stats.vercel.app/api?username=SupunVirajDevendra&theme=radical&hide_border=false&show_icons=true&include_all_commits=true&count_private=true"
                alt="Supun's GitHub stats">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=SupunVirajDevendra&theme=radical&hide_border=false"
                alt="Supun's GitHub Streak">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SupunVirajDevendra&theme=radical&hide_border=false&include_all_commits=true&count_private=true&layout=compact"
                alt="Top Languages">
        </div>
    </section>

    <section class="section">
        <h2>🌐 Connect with Me</h2>
        <div class="social-links">
            <a href="https://web.facebook.com/supundevendra12/" target="_blank">
                <img src="https://img.shields.io/badge/Facebook-1877F2?logo=facebook&logoColor=white&style=for-the-badge"
                    alt="Supun Devendra Facebook">
            </a>
            <a href="https://instagram.com/supundevendra" target="_blank">
                <img src="https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white&style=for-the-badge"
                    alt="Supun Devendra Instagram">
            </a>
            <a href="https://discord.gg/deva2598" target="_blank">
                <img src="https://img.shields.io/badge/Discord-5865F2?logo=discord&logoColor=white&style=for-the-badge"
                    alt="Supun Devendra Discord">
            </a>
        </div>
    </section>

    <div class="footer">
        <p>🛠️ Proudly created with GPRM ( <a href="https://gprm.itsvg.in" target="_blank">https://gprm.itsvg.in</a> )</p>
    </div>
</body>

</html>
