<!DOCTYPE html>
<html lang="ru">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
    body {
        font-family: FiraCode, sans-serif;
        font-size: 22px; /* Базовый размер шрифта */
        padding: 0;
        line-height: 1.6;
    }
    .centered {
        text-align: center;
    }
    .intro img {
        max-width: 100%;
        height: auto;
    }
    .profile-details img {
        max-width: 100%;
        height: auto;
    }
    .right {
        float: right;
        margin: 0 1rem 1rem 0;
        max-width: 60%; /* Чтобы картинка не занимала слишком много места на малых экранах */
    }
    .profile-details ul,
    .knowledge-skills ul {
        list-style-type: none;
        padding: 0;
    }
    .profile-details ul li,
    .knowledge-skills ul li {
        margin-bottom: 0.5rem;
        text-align: left; /* Выравнивание элементов списка по левому краю */
    }
    .knowledge-skills img {
        width: 60%;
        height: 60%;
    }
    a {
        color: #0073e6;
        text-decoration: none;
    }
    a:hover {
        text-decoration: underline;
    }
    .github-stats {
        display: flex;
        justify-content: center;
        gap: 1.25rem;
    }
    hr {
        border: 1px solid #ccc;
        margin: 1.25rem 0;
    }
    @media (max-width: 1200px) {
        body {
            font-size: 18px; /* Уменьшение размера шрифта для экранов до 1200px */
        }
    }
    @media (max-width: 992px) {
        body {
            font-size: 16px; /* Уменьшение размера шрифта для экранов до 992px */
        }
        .right {
            float: right;
            margin: 0 1rem 1rem 0;
            max-width: 80%; /* Чтобы картинка не занимала слишком много места на малых экранах */
        }
        .knowledge-skills img {
            width: 90%;
            height: 70%;
        }
    }
    @media (max-width: 768px) {
        body {
            font-size: 14px; /* Уменьшение размера шрифта для экранов до 768px */
        }
        .github-stats {
            flex-direction: column;
            gap: 0.5rem;
        }
    }
</style>

<body>
    <h1 class="centered">~ 💖 Welcome to my profile 💖 ~</h1>
    <br>
    <div class="intro centered">
        <img src="assets/github-snake.svg" alt="Snake">
        <br><br>
        <h4>Hi there, I'm <a href="https://github.com/C3EQUALZz/C3EQUALZz" target="_blank">Danil Kovalev</a></h4>
        <h4>I'm self-taught passionate in CyberSecurity and Developing</h4>
    </div>
    <div class="profile-details">
        <hr>
        <h2 class="centered">~ About me ~</h2>
        <div class="right">
            <img src="https://cdn140.picsart.com/287425545055211.png" alt="Profile Image">
        </div>
        <ul>
            <li><b>Name:</b> Danil</li>
            <li><b>Surname:</b> Kovalev</li>
            <li><b>Nickname:</b> c3equalz</li>
            <li><b>Loves:</b> programming, anime, math</li>
            <li><b>Gender:</b> he/his/male</li>
            <li><b>Experience:</b> none</li>
        </ul>
        <p>I am a beginner developer. My journey into the IT world began quite recently as I am currently a university student. During my free time, I strive to expand my knowledge by taking various courses. I am particularly interested in backend development with Python and information security. As a beginner in this field, I am actively studying all aspects to become a qualified specialist who can help protect companies and organizations from cyberattacks. You can find my projects and research on my GitHub account, and I am always open to collaborating and communicating with other experts in the field.</p>
        <br>
        <hr>
    </div>
    <div class="knowledge-skills">
        <h2 class="centered">~ 📇 Knowledge and Skills 📇 ~</h2>
        <br>
        <div class="centered">
            <a href="https://github.com/C3EQUALZz">
                <img src="https://skillicons.dev/icons?i=python,java,ts,html,css,pycharm,idea,webstorm,qt,fastapi,selenium,tensorflow,sklearn,regex,postgres,mysql,mongodb,redis,rabbitmq,cloudflare,linux,bash,powershell" alt="Skills Icons">
                <br><br>
            </a>
        </div>
    </div>
    <div class="profile-details">
        <ul>
            <li>🌱 Python, Object-Oriented Programming (OOP), SQL, Git, Bash</li>
            <li>🔭 Metasploit, Nmap, Wireshark, Airmon-ng, Snoop, hacking passwords, OSINT</li>
            <li>🤔 Requests, BeautifulSoup4, Selenium, Asyncio</li>
            <li>🤓 Agile Methodologies, Clean code, SOLID, KISS, DRY</li>
            <li>📝 Languages: English (Upper-intermediate) B2, Russian (Native) C2</li>
        </ul>
        <br>
        <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&width=435&lines=Certificates+for+completed+courses:" alt="Typing SVG"></a>
        <ul>
            <li><a href="https://stepik.org/cert/1560586">Stepik course - "Поколение Python": курс для начинающих</a></li>
            <li><a href="https://stepik.org/cert/1909905">Stepik course - "Поколение Python": курс для продвинутых</a></li>
            <li><a href="https://stepik.org/cert/2136212">Stepik course - "Поколение Python": курс для профессионалов</a></li>
            <li><a href="https://stepik.org/cert/2157118">Stepik course - "Поколение Python": ООП</a></li>
            <li><a href="https://stepik.org/cert/1932793">Stepik course - Инди-курс программирования на Python</a></li>
            <li><a href="https://stepik.org/cert/2074813">Stepik course - Введение в Linux</a></li>
            <li><a href="https://stepik.org/cert/2360757">Stepik course - Java с нуля до Junior + Подготовка к собеседованию</a></li>
        </ul>
        <br>
        <hr>
    </div>
    <div class="github-stats">
        <a href="https://github.com/anuraghazra/github-readme-stats">
            <img src="https://github-readme-stats.vercel.app/api?username=C3EQUALZz&show_icons=true&include_all_commits=true&theme=dracula&hide_border=true" alt="GitHub Stats">
        </a>
        <a href="https://github.com/anuraghazra/github-readme-stats">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=C3EQUALZz&layout=compact&theme=dracula&hide_border=true" alt="Top Languages">
        </a>
    </div>
</body>
</html>
