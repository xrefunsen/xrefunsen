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
            line-height: 1.6;
            color: #24292f;
            background: #ffffff;
            max-width: 1012px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
            border-bottom: 1px solid #d0d7de;
            padding-bottom: 30px;
        }

        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin-bottom: 20px;
            border: 3px solid #d0d7de;
        }

        .name {
            font-size: 2rem;
            font-weight: 600;
            color: #0969da;
            margin-bottom: 8px;
        }

        .title {
            font-size: 1.2rem;
            color: #656d76;
            margin-bottom: 16px;
        }

        .subtitle {
            font-size: 1rem;
            color: #656d76;
            margin-bottom: 20px;
        }

        .github-link {
            display: inline-block;
            padding: 8px 16px;
            background: #0969da;
            color: white;
            text-decoration: none;
            border-radius: 6px;
            font-weight: 500;
            transition: background-color 0.2s;
        }

        .github-link:hover {
            background: #0860ca;
        }

        .section {
            margin-bottom: 32px;
        }

        .section-title {
            font-size: 1.5rem;
            font-weight: 600;
            color: #24292f;
            margin-bottom: 16px;
            padding-bottom: 8px;
            border-bottom: 1px solid #d0d7de;
        }

        .about {
            background: #f6f8fa;
            padding: 20px;
            border-radius: 6px;
            border: 1px solid #d0d7de;
            margin-bottom: 24px;
        }

        .about p {
            margin-bottom: 12px;
            color: #24292f;
        }

        .about p:last-child {
            margin-bottom: 0;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-bottom: 24px;
        }

        .skill-category {
            background: #ffffff;
            padding: 20px;
            border-radius: 6px;
            border: 1px solid #d0d7de;
            transition: box-shadow 0.2s;
        }

        .skill-category:hover {
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
        }

        .skill-category h3 {
            color: #24292f;
            margin-bottom: 12px;
            font-size: 1.1rem;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .skill-icon {
            width: 20px;
            height: 20px;
            border-radius: 3px;
            display: inline-block;
        }

        .cyber-security {
            border-left: 4px solid #d73a49;
        }

        .fullstack {
            border-left: 4px solid #0366d6;
        }


        .languages-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            gap: 16px;
            margin-top: 16px;
        }

        .language-item {
            text-align: center;
            padding: 12px;
            background: #f6f8fa;
            border-radius: 6px;
            border: 1px solid #d0d7de;
            transition: background-color 0.2s;
        }

        .language-item:hover {
            background: #f1f3f4;
        }

        .language-logo {
            width: 40px;
            height: 40px;
            margin: 0 auto 8px;
            display: block;
        }

        .language-name {
            font-weight: 500;
            color: #24292f;
            font-size: 0.9rem;
        }


        .footer {
            border-top: 1px solid #d0d7de;
            padding-top: 20px;
            text-align: center;
            color: #656d76;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            body {
                padding: 20px 16px;
            }
            
            .name {
                font-size: 1.5rem;
            }
            
            .skills-grid {
                grid-template-columns: 1fr;
            }
            
            .languages-grid {
                grid-template-columns: repeat(auto-fit, minmax(80px, 1fr));
            }
            
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="https://avatars.githubusercontent.com/u/150449604?v=4" alt="Ali Ramazan" class="profile-img">
        <h1 class="name">Ali Ramazan</h1>
        <p class="title">Fullstack Developer & Cyber Security Specialist</p>
        <p class="subtitle">Grey Hat Hacker</p>
        <a href="https://github.com/xrefunsen" class="github-link" target="_blank">GitHub</a>
    </div>

    <main>
        <section class="about section">
            <h2 class="section-title">Hakkımda</h2>
            <p>Merhaba! Ben Ali Ramazan. Tutkulu bir yazılım geliştirici olarak, teknoloji dünyasında kendimi sürekli geliştiren bir profesyonelim.</p>
            
            <p><strong>Siber Güvenlik</strong> alanında uzmanlaşmış, gri hacker yaklaşımıyla güvenlik testleri yapan, sistemleri korumak için saldırgan düşünce yapısını anlayan bir güvenlik uzmanıyım.</p>
            
            <p><strong>Fullstack Development</strong> konusunda deneyimli, frontend'den backend'e, veritabanından deployment'a kadar tüm süreçleri yönetebilen bir geliştiriciyim.</p>
            
            <p>Sürekli öğrenmeyi seven, teknoloji dünyasının hızına ayak uyduran ve her yeni projeyle kendini geliştiren bir geliştiriciyim.</p>
        </section>

        <section class="section">
            <h2 class="section-title">Uzmanlık Alanları</h2>
            <div class="skills-grid">
                <div class="skill-category cyber-security">
                    <h3>
                        <span class="skill-icon" style="background: #d73a49;"></span>
                        Siber Güvenlik
                    </h3>
                    <p>Penetrasyon testleri, güvenlik açığı analizi ve siber güvenlik danışmanlığı konularında deneyimli. Gri hacker yaklaşımıyla güvenlik testleri yapıyorum.</p>
                </div>

                <div class="skill-category fullstack">
                    <h3>
                        <span class="skill-icon" style="background: #0366d6;"></span>
                        Fullstack Development
                    </h3>
                    <p>Frontend'den backend'e, veritabanından deployment'a kadar tüm süreçleri yönetebilen tam kapsamlı web uygulamaları geliştiriyorum.</p>
                </div>

            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Programlama Dilleri</h2>
            <div class="languages-grid">
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" class="language-logo">
                    <div class="language-name">Java</div>
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
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP" class="language-logo">
                    <div class="language-name">PHP</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" class="language-logo">
                    <div class="language-name">TypeScript</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" alt="Go" class="language-logo">
                    <div class="language-name">Go</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" alt="Rust" class="language-logo">
                    <div class="language-name">Rust</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" alt="Kotlin" class="language-logo">
                    <div class="language-name">Kotlin</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/swift/swift-original.svg" alt="Swift" class="language-logo">
                    <div class="language-name">Swift</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ruby/ruby-original.svg" alt="Ruby" class="language-logo">
                    <div class="language-name">Ruby</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/lua/lua-original.svg" alt="Lua" class="language-logo">
                    <div class="language-name">Lua</div>
                </div>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Web Uygulamaları</h2>
            <div class="languages-grid">
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
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap" class="language-logo">
                    <div class="language-name">Bootstrap</div>
                </div>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Siber Güvenlik & DevOps</h2>
            <div class="languages-grid">
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux" class="language-logo">
                    <div class="language-name">Linux</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" alt="Bash" class="language-logo">
                    <div class="language-name">Bash</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" class="language-logo">
                    <div class="language-name">Docker</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" class="language-logo">
                    <div class="language-name">Git</div>
                </div>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Veritabanları</h2>
            <div class="languages-grid">
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" class="language-logo">
                    <div class="language-name">MySQL</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" alt="SQLite" class="language-logo">
                    <div class="language-name">SQLite</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" class="language-logo">
                    <div class="language-name">PostgreSQL</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB" class="language-logo">
                    <div class="language-name">MongoDB</div>
                </div>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Model & Game Engines</h2>
            <div class="languages-grid">
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unity/unity-original.svg" alt="Unity" class="language-logo">
                    <div class="language-name">Unity</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unrealengine/unrealengine-original.svg" alt="Unreal Engine" class="language-logo">
                    <div class="language-name">Unreal Engine</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/blender/blender-original.svg" alt="Blender" class="language-logo">
                    <div class="language-name">Blender</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/autodesk/autodesk-original.svg" alt="3ds Max" class="language-logo">
                    <div class="language-name">3ds Max</div>
                </div>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Cloud & Platform</h2>
            <div class="languages-grid">
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" alt="AWS" class="language-logo">
                    <div class="language-name">AWS</div>
                </div>
                <div class="language-item">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" alt="Azure" class="language-logo">
                    <div class="language-name">Azure</div>
                </div>
            </div>
        </section>

    </main>

    <footer class="footer">
        <p>&copy; 2024 Ali Ramazan. Tüm hakları saklıdır. | Gri Hacker & Fullstack Developer</p>
    </footer>
</body>
</html>
