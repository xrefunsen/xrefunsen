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
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            backdrop-filter: blur(10px);
        }

        .header {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: white;
            padding: 40px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, transparent 70%);
            animation: float 6s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(180deg); }
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid rgba(255, 255, 255, 0.3);
            margin: 0 auto 20px;
            display: block;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            position: relative;
            z-index: 1;
        }

        .name {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 10px;
            position: relative;
            z-index: 1;
        }

        .title {
            font-size: 1.3rem;
            opacity: 0.9;
            margin-bottom: 20px;
            position: relative;
            z-index: 1;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            position: relative;
            z-index: 1;
        }

        .social-link {
            display: inline-block;
            padding: 10px 20px;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 25px;
            text-decoration: none;
            color: white;
            transition: all 0.3s ease;
            border: 2px solid transparent;
        }

        .social-link:hover {
            background: rgba(255, 255, 255, 0.3);
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        .content {
            padding: 40px;
        }

        .section {
            margin-bottom: 40px;
        }

        .section-title {
            font-size: 1.8rem;
            color: #2c3e50;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 3px solid #3498db;
            position: relative;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: -3px;
            left: 0;
            width: 50px;
            height: 3px;
            background: #e74c3c;
        }

        .about {
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            padding: 30px;
            border-radius: 15px;
            border-left: 5px solid #3498db;
            margin-bottom: 30px;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }

        .skill-category {
            background: white;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .skill-category:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
        }

        .skill-category h3 {
            color: #2c3e50;
            margin-bottom: 15px;
            font-size: 1.3rem;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .skill-icon {
            width: 30px;
            height: 30px;
            border-radius: 5px;
            display: inline-block;
        }

        .languages-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .language-item {
            text-align: center;
            padding: 15px;
            background: #f8f9fa;
            border-radius: 10px;
            transition: all 0.3s ease;
            border: 2px solid transparent;
        }

        .language-item:hover {
            background: #e9ecef;
            border-color: #3498db;
            transform: scale(1.05);
        }

        .language-logo {
            width: 50px;
            height: 50px;
            margin: 0 auto 10px;
            border-radius: 8px;
            display: block;
        }

        .language-name {
            font-weight: 600;
            color: #2c3e50;
            font-size: 0.9rem;
        }

        .cyber-security {
            background: linear-gradient(135deg, #e74c3c 0%, #c0392b 100%);
            color: white;
        }

        .cyber-security h3 {
            color: white;
        }

        .game-dev {
            background: linear-gradient(135deg, #9b59b6 0%, #8e44ad 100%);
            color: white;
        }

        .game-dev h3 {
            color: white;
        }

        .fullstack {
            background: linear-gradient(135deg, #3498db 0%, #2980b9 100%);
            color: white;
        }

        .fullstack h3 {
            color: white;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
        }

        .project-card {
            background: white;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            border-top: 4px solid #3498db;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
        }

        .project-title {
            font-size: 1.2rem;
            font-weight: 600;
            color: #2c3e50;
            margin-bottom: 10px;
        }

        .project-description {
            color: #666;
            margin-bottom: 15px;
        }

        .project-tech {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }

        .tech-tag {
            background: #ecf0f1;
            padding: 5px 12px;
            border-radius: 15px;
            font-size: 0.8rem;
            color: #2c3e50;
        }

        .contact-info {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: white;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .contact-item {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            padding: 15px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            transition: all 0.3s ease;
        }

        .contact-item:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: scale(1.05);
        }

        .footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            .container {
                margin: 10px;
                border-radius: 15px;
            }
            
            .header {
                padding: 30px 20px;
            }
            
            .name {
                font-size: 2rem;
            }
            
            .content {
                padding: 30px 20px;
            }
            
            .social-links {
                flex-direction: column;
                align-items: center;
            }
        }

        .pulse {
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        .hacker-text {
            background: linear-gradient(45deg, #ff0000, #00ff00, #0000ff, #ffff00);
            background-size: 400% 400%;
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: gradientShift 3s ease infinite;
        }

        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <img src="https://avatars.githubusercontent.com/u/150449604?v=4" alt="Ali Ramazan" class="profile-img">
            <h1 class="name">Ali Ramazan</h1>
            <p class="title">Fullstack Developer & Cyber Security Specialist</p>
            <div class="social-links">
                <a href="https://github.com/xrefunsen" class="social-link" target="_blank">GitHub</a>
                <a href="#" class="social-link">LinkedIn</a>
                <a href="#" class="social-link">Email</a>
            </div>
        </header>

        <main class="content">
            <section class="about section">
                <h2 class="section-title">Hakkımda</h2>
                <p>Merhaba! Ben Ali Ramazan, tutkulu bir yazılım geliştiriciyim. Siber güvenlik alanında uzmanlaşmış, fullstack web geliştirme konusunda deneyimli ve oyun geliştirme konusunda çalışmalar yapan bir geliştiriciyim. Sürekli öğrenmeyi seven, teknoloji dünyasının hızına ayak uyduran bir profesyonelim.</p>
            </section>

            <section class="section">
                <h2 class="section-title">Uzmanlık Alanları</h2>
                <div class="skills-grid">
                    <div class="skill-category cyber-security">
                        <h3>
                            <span class="skill-icon" style="background: #e74c3c;">🔒</span>
                            Siber Güvenlik
                        </h3>
                        <p>Penetrasyon testleri, güvenlik açığı analizi ve siber güvenlik danışmanlığı konularında deneyimli. Gri hacker yaklaşımıyla güvenlik testleri yapıyorum.</p>
                    </div>

                    <div class="skill-category fullstack">
                        <h3>
                            <span class="skill-icon" style="background: #3498db;">🌐</span>
                            Fullstack Development
                        </h3>
                        <p>Frontend'den backend'e, veritabanından deployment'a kadar tüm süreçleri yönetebilen tam kapsamlı web uygulamaları geliştiriyorum.</p>
                    </div>

                    <div class="skill-category game-dev">
                        <h3>
                            <span class="skill-icon" style="background: #9b59b6;">🎮</span>
                            Game Development
                        </h3>
                        <p>Oyun geliştirme konusunda çalışmalar yapıyorum. Farklı oyun motorları ve programlama dilleri kullanarak projeler geliştiriyorum.</p>
                    </div>
                </div>
            </section>

            <section class="section">
                <h2 class="section-title">Programlama Dilleri & Teknolojiler</h2>
                <div class="languages-grid">
                    <div class="language-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" class="language-logo">
                        <div class="language-name">Java</div>
                    </div>
                    <div class="language-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP" class="language-logo">
                        <div class="language-name">PHP</div>
                    </div>
                    <div class="language-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" class="language-logo">
                        <div class="language-name">JavaScript</div>
                    </div>
                    <div class="language-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" class="language-logo">
                        <div class="language-name">C#</div>
                    </div>
                    <div class="language-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C" class="language-logo">
                        <div class="language-name">C</div>
                    </div>
                    <div class="language-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++" class="language-logo">
                        <div class="language-name">C++</div>
                    </div>
                    <div class="language-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" class="language-logo">
                        <div class="language-name">Python</div>
                    </div>
                    <div class="language-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" class="language-logo">
                        <div class="language-name">HTML5</div>
                    </div>
                    <div class="language-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" class="language-logo">
                        <div class="language-name">CSS3</div>
                    </div>
                    <div class="language-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" class="language-logo">
                        <div class="language-name">Node.js</div>
                    </div>
                    <div class="language-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" class="language-logo">
                        <div class="language-name">React</div>
                    </div>
                    <div class="language-item">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" class="language-logo">
                        <div class="language-name">MySQL</div>
                    </div>
                </div>
            </section>

            <section class="section">
                <h2 class="section-title">Projeler</h2>
                <div class="projects">
                    <div class="project-card">
                        <h3 class="project-title">Bug Reports Plugin</h3>
                        <p class="project-description">Spigot için geliştirilmiş kapsamlı bug raporlama sistemi. Minecraft sunucuları için gelişmiş hata takip ve yönetim aracı.</p>
                        <div class="project-tech">
                            <span class="tech-tag">Java</span>
                            <span class="tech-tag">Spigot API</span>
                            <span class="tech-tag">MySQL</span>
                        </div>
                    </div>
                    <div class="project-card">
                        <h3 class="project-title">Cyber Security Toolkit</h3>
                        <p class="project-description">Siber güvenlik uzmanları için geliştirilmiş kapsamlı araç seti. Penetrasyon testleri ve güvenlik analizi için gerekli araçları içerir.</p>
                        <div class="project-tech">
                            <span class="tech-tag">Python</span>
                            <span class="tech-tag">Network Security</span>
                            <span class="tech-tag">Penetration Testing</span>
                        </div>
                    </div>
                    <div class="project-card">
                        <h3 class="project-title">Game Development Framework</h3>
                        <p class="project-description">Oyun geliştirme süreçlerini hızlandıran özel framework. Farklı oyun türleri için modüler yapı sunar.</p>
                        <div class="project-tech">
                            <span class="tech-tag">C++</span>
                            <span class="tech-tag">OpenGL</span>
                            <span class="tech-tag">Game Engine</span>
                        </div>
                    </div>
                </div>
            </section>

            <section class="section">
                <h2 class="section-title">İletişim</h2>
                <div class="contact-info">
                    <h3>Benimle İletişime Geçin</h3>
                    <div class="contact-grid">
                        <div class="contact-item">
                            <span>📧</span>
                            <span>ali.ramazan@example.com</span>
                        </div>
                        <div class="contact-item">
                            <span>🌐</span>
                            <span>github.com/xrefunsen</span>
                        </div>
                        <div class="contact-item">
                            <span>💼</span>
                            <span>LinkedIn Profile</span>
                        </div>
                        <div class="contact-item">
                            <span>📍</span>
                            <span>Türkiye</span>
                        </div>
                    </div>
                </div>
            </section>
        </main>

        <footer class="footer">
            <p>&copy; 2024 Ali Ramazan. Tüm hakları saklıdır. | <span class="hacker-text">Gri Hacker & Fullstack Developer</span></p>
        </footer>
    </div>
</body>
</html>
