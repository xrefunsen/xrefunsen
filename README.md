<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ali Ramazan - Fullstack Developer & Cyber Security Specialist</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Noto Sans', Helvetica, Arial, sans-serif;
            background: #282a36;
            color: #f8f8f2;
            line-height: 1.6;
            padding: 20px;
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
            padding: 30px 0;
            border-bottom: 1px solid #44475a;
        }

        .profile-img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 20px;
            border: 3px solid #50fa7b;
        }

        .name {
            font-size: 2.5rem;
            font-weight: 700;
            color: #50fa7b;
            margin-bottom: 10px;
        }

        .title {
            font-size: 1.2rem;
            color: #bd93f9;
            margin-bottom: 20px;
        }

        .github-link {
            display: inline-block;
            padding: 10px 20px;
            background: #6272a4;
            color: #f8f8f2;
            text-decoration: none;
            border-radius: 8px;
            font-weight: 500;
            transition: background-color 0.3s;
        }

        .github-link:hover {
            background: #44475a;
        }

        .section {
            margin-bottom: 40px;
        }

        .section-title {
            font-size: 1.5rem;
            font-weight: 600;
            color: #f8f8f2;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .section-icon {
            font-size: 1.2rem;
        }

        .about {
            background: #44475a;
            padding: 25px;
            border-radius: 10px;
            margin-bottom: 30px;
            border-left: 4px solid #50fa7b;
        }

        .about p {
            margin-bottom: 12px;
            color: #f8f8f2;
        }

        .about p:last-child {
            margin-bottom: 0;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .skill-category {
            background: #44475a;
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #ff79c6;
        }

        .skill-category h3 {
            color: #f8f8f2;
            margin-bottom: 12px;
            font-size: 1.1rem;
            font-weight: 600;
        }

        .cyber-security {
            border-left-color: #ff5555;
        }

        .fullstack {
            border-left-color: #8be9fd;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 12px;
            margin-top: 15px;
        }

        .badge {
            display: inline-block;
            margin: 4px;
            border-radius: 6px;
            overflow: hidden;
            transition: transform 0.2s;
        }

        .badge:hover {
            transform: translateY(-2px);
        }

        .badge img {
            display: block;
            height: 28px;
        }

        .github-stats {
            display: flex;
            flex-direction: column;
            gap: 20px;
            margin-top: 30px;
        }

        .github-stats img {
            max-width: 100%;
            border-radius: 8px;
        }

        .tech-category {
            margin-bottom: 30px;
        }

        .tech-category h3 {
            color: #bd93f9;
            margin-bottom: 15px;
            font-size: 1.2rem;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .footer {
            text-align: center;
            padding: 20px 0;
            border-top: 1px solid #44475a;
            color: #6272a4;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            body {
                padding: 15px;
            }
            
            .name {
                font-size: 2rem;
            }
            
            .skills-grid {
                grid-template-columns: 1fr;
            }
            
            .tech-grid {
                grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <img src="https://avatars.githubusercontent.com/u/150449604?v=4" alt="Ali Ramazan" class="profile-img">
            <h1 class="name">Ali Ramazan</h1>
            <p class="title">Fullstack Developer & Cyber Security Specialist</p>
            
            <div class="section">
                <h2 class="section-title">
                    <span class="section-icon">🌐</span>
                    Socials:
                </h2>
                <div style="margin-bottom: 20px;">
                    <a href="https://github.com/xrefunsen" target="_blank" class="badge">
                        <img src="https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
                    </a>
                    <a href="#" target="_blank" class="badge">
                        <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
                    </a>
                    <a href="mailto:ali.ramazan@example.com" class="badge">
                        <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
                    </a>
                </div>
            </div>
        </header>

        <main>
            <section class="about section">
                <h2 class="section-title">
                    <span class="section-icon">👋</span>
                    Hakkımda
                </h2>
                <p>Merhaba! Ben Ali Ramazan. Tutkulu bir yazılım geliştirici olarak, teknoloji dünyasında kendimi sürekli geliştiren bir profesyonelim.</p>
                
                <p><strong>Siber Güvenlik</strong> alanında uzmanlaşmış, gri hacker yaklaşımıyla güvenlik testleri yapan, sistemleri korumak için saldırgan düşünce yapısını anlayan bir güvenlik uzmanıyım.</p>
                
                <p><strong>Fullstack Development</strong> konusunda deneyimli, frontend'den backend'e, veritabanından deployment'a kadar tüm süreçleri yönetebilen bir geliştiriciyim.</p>
                
                <p>Sürekli öğrenmeyi seven, teknoloji dünyasının hızına ayak uyduran ve her yeni projeyle kendini geliştiren bir geliştiriciyim.</p>
            </section>

            <section class="section">
                <h2 class="section-title">
                    <span class="section-icon">🎯</span>
                    Uzmanlık Alanları
                </h2>
                <div class="skills-grid">
                    <div class="skill-category cyber-security">
                        <h3>🔒 Siber Güvenlik</h3>
                        <p>Penetrasyon testleri, güvenlik açığı analizi ve siber güvenlik danışmanlığı konularında deneyimli. Gri hacker yaklaşımıyla güvenlik testleri yapıyorum.</p>
                    </div>

                    <div class="skill-category fullstack">
                        <h3>🌐 Fullstack Development</h3>
                        <p>Frontend'den backend'e, veritabanından deployment'a kadar tüm süreçleri yönetebilen tam kapsamlı web uygulamaları geliştiriyorum.</p>
                    </div>
                </div>
            </section>

            <section class="section">
                <h2 class="section-title">
                    <span class="section-icon">💻</span>
                    Tech Stack:
                </h2>
                
                <div style="margin-bottom: 20px;">
                    <span class="badge">
                        <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white" alt="C#">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white" alt="Go">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white" alt="Rust">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/swift-FA7343?style=for-the-badge&logo=swift&logoColor=white" alt="Swift">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white" alt="Ruby">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white" alt="Lua">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="NodeJS">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white" alt="Unity">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white" alt="Unreal Engine">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/blender-%23F5792A.svg?style=for-the-badge&logo=blender&logoColor=white" alt="Blender">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/3ds%20Max-%230696D7.svg?style=for-the-badge&logo=autodesk&logoColor=white" alt="3ds Max">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/Amazon%20AWS-%23FF9900.svg?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS">
                    </span>
                    <span class="badge">
                        <img src="https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=azure-devops&logoColor=white" alt="Azure">
                    </span>
                </div>
            </section>

            <section class="section">
                <h2 class="section-title">
                    <span class="section-icon">📊</span>
                    GitHub Stats:
                </h2>
                
                <div class="github-stats">
                    <img src="https://github-readme-stats.vercel.app/api?username=xrefunsen&theme=dark&hide_border=false&include_all_commits=true&count_private=true" alt="GitHub Stats">
                    <img src="https://github-readme-streak-stats.herokuapp.com/?user=xrefunsen&theme=dark&hide_border=false" alt="GitHub Streak">
                    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=xrefunsen&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact" alt="Top Languages">
                </div>
            </section>
        </main>

        <footer class="footer">
            <p>&copy; 2024 Ali Ramazan. Tüm hakları saklıdır. | Gri Hacker & Fullstack Developer</p>
        </footer>
    </div>
</body>
</html>
