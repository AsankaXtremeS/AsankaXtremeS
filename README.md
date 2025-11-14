<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Asanka's GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
            background: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            padding: 40px 20px;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            margin-bottom: 50px;
            border-bottom: 1px solid #30363d;
            padding-bottom: 30px;
        }
        
        .greeting {
            font-size: 28px;
            font-weight: 600;
            margin-bottom: 10px;
            color: #58a6ff;
        }
        
        .subtitle {
            font-size: 16px;
            color: #8b949e;
            margin-bottom: 5px;
        }
        
        .section {
            margin-bottom: 40px;
        }
        
        .section-title {
            font-size: 20px;
            font-weight: 600;
            margin-bottom: 20px;
            color: #58a6ff;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .section-title::before {
            content: '';
            display: inline-block;
            width: 4px;
            height: 20px;
            background: #58a6ff;
            border-radius: 2px;
        }
        
        .about-content {
            background: #161b22;
            padding: 25px;
            border-radius: 6px;
            border-left: 3px solid #58a6ff;
        }
        
        .about-item {
            margin-bottom: 15px;
            display: flex;
            align-items: flex-start;
            gap: 12px;
        }
        
        .about-item:last-child {
            margin-bottom: 0;
        }
        
        .about-icon {
            font-size: 20px;
            min-width: 24px;
        }
        
        .about-text {
            color: #c9d1d9;
        }
        
        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .tech-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
            padding: 15px;
            background: #161b22;
            border-radius: 6px;
            transition: all 0.3s ease;
            border: 1px solid #30363d;
        }
        
        .tech-item:hover {
            background: #0d1117;
            border-color: #58a6ff;
            transform: translateY(-2px);
        }
        
        .tech-icon {
            width: 40px;
            height: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .tech-icon img {
            width: 100%;
            height: 100%;
            object-fit: contain;
        }
        
        .tech-name {
            font-size: 12px;
            text-align: center;
            color: #8b949e;
            font-weight: 500;
        }
        
        .category {
            margin-bottom: 30px;
        }
        
        .category-title {
            font-size: 14px;
            font-weight: 600;
            color: #79c0ff;
            margin-bottom: 12px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }
        
        .contact-section {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            align-items: center;
            justify-content: center;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 8px;
            padding: 10px 15px;
            background: #161b22;
            border-radius: 6px;
            border: 1px solid #30363d;
            text-decoration: none;
            color: #58a6ff;
            transition: all 0.3s ease;
        }
        
        .contact-item:hover {
            border-color: #58a6ff;
            background: #0d1117;
        }
        
        .contact-icon {
            width: 20px;
            height: 20px;
        }
        
        .footer {
            text-align: center;
            margin-top: 50px;
            padding-top: 30px;
            border-top: 1px solid #30363d;
            color: #8b949e;
            font-size: 13px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <div class="header">
            <div class="greeting">👋 Hi, I'm Asanka</div>
            <div class="subtitle">Full Stack Developer | IT BSc (Hons) Student</div>
            <div class="subtitle">Passionate about web development and problem-solving</div>
        </div>

        <!-- About Section -->
        <div class="section">
            <div class="section-title">About Me</div>
            <div class="about-content">
                <div class="about-item">
                    <span class="about-icon">🔭</span>
                    <span class="about-text"><strong>Current Focus:</strong> Building scalable web applications with modern tech stack</span>
                </div>
                <div class="about-item">
                    <span class="about-icon">🎓</span>
                    <span class="about-text"><strong>Education:</strong> Pursuing IT Bachelor of Science (Hons)</span>
                </div>
                <div class="about-item">
                    <span class="about-icon">🌱</span>
                    <span class="about-text"><strong>Learning:</strong> Constantly exploring new technologies and best practices</span>
                </div>
                <div class="about-item">
                    <span class="about-icon">💡</span>
                    <span class="about-text"><strong>Expertise:</strong> Problem-solving, algorithm design, and clean code architecture</span>
                </div>
                <div class="about-item">
                    <span class="about-icon">⚡</span>
                    <span class="about-text"><strong>Passion:</strong> Quick learner with a drive to master new technologies</span>
                </div>
            </div>
        </div>

        <!-- Tech Stack Section -->
        <div class="section">
            <div class="section-title">Tech Stack</div>
            
            <div class="category">
                <div class="category-title">Frontend</div>
                <div class="tech-grid">
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5">
                        </div>
                        <div class="tech-name">HTML5</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3">
                        </div>
                        <div class="tech-name">CSS3</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
                        </div>
                        <div class="tech-name">JavaScript</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript">
                        </div>
                        <div class="tech-name">TypeScript</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="Next.js">
                        </div>
                        <div class="tech-name">Next.js</div>
                    </div>
                </div>
            </div>

            <div class="category">
                <div class="category-title">Backend & Database</div>
                <div class="tech-grid">
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
                        </div>
                        <div class="tech-name">Java</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB">
                        </div>
                        <div class="tech-name">MongoDB</div>
                    </div>
                </div>
            </div>

            <div class="category">
                <div class="category-title">Mobile Development</div>
                <div class="tech-grid">
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" alt="Flutter">
                        </div>
                        <div class="tech-name">Flutter</div>
                    </div>
                </div>
            </div>

            <div class="category">
                <div class="category-title">Core Programming</div>
                <div class="tech-grid">
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C">
                        </div>
                        <div class="tech-name">C</div>
                    </div>
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++">
                        </div>
                        <div class="tech-name">C++</div>
                    </div>
                </div>
            </div>

            <div class="category">
                <div class="category-title">Tools & Version Control</div>
                <div class="tech-grid">
                    <div class="tech-item">
                        <div class="tech-icon">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git">
                        </div>
                        <div class="tech-name">Git</div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Connect Section -->
        <div class="section">
            <div class="section-title">Get In Touch</div>
            <div class="contact-section">
                <a href="mailto:asankasampath200228@gmail.com" class="contact-item">
                    <span>📧</span>
                    <span>Email</span>
                </a>
                <a href="https://www.linkedin.com/in/asanka-sampath-a5b5b42a9" target="_blank" class="contact-item">
                    <span>💼</span>
                    <span>LinkedIn</span>
                </a>
            </div>
        </div>

        <!-- Footer -->
        <div class="footer">
            <p>⭐ Feel free to explore my repositories and connect with me!</p>
        </div>
    </div>
</body>
</html>
