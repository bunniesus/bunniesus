<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shravani's GitHub Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0d1117 0%, #161b22 100%);
            color: #c9d1d9;
            line-height: 1.6;
            padding: 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        
        .container {
            background-color: #161b22;
            border-radius: 15px;
            padding: 30px;
            margin: 20px 0;
            border: 1px solid #30363d;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
        }
        
        header {
            text-align: center;
            padding: 20px 0;
        }
        
        h1 {
            color: #58a6ff;
            margin-bottom: 10px;
            font-size: 2.5rem;
        }
        
        h2 {
            color: #f78166;
            margin: 20px 0 10px;
            border-bottom: 1px solid #30363d;
            padding-bottom: 5px;
        }
        
        h3 {
            color: #58a6ff;
            margin: 15px 0 10px;
        }
        
        p {
            margin-bottom: 15px;
        }
        
        .highlight {
            color: #f78166;
            font-weight: bold;
        }
        
        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 15px 0;
        }
        
        .badge {
            background: linear-gradient(135deg, #238636 0%, #2ea043 100%);
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
            gap: 5px;
        }
        
        .badge-art {
            background: linear-gradient(135deg, #6e40c9 0%, #8e6cef 100%);
        }
        
        .badge-design {
            background: linear-gradient(135deg, #db61a2 0%, #e16db4 100%);
        }
        
        .links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin: 20px 0;
        }
        
        .link {
            color: #58a6ff;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 8px;
            padding: 8px 16px;
            border: 1px solid #30363d;
            border-radius: 6px;
            transition: all 0.3s ease;
        }
        
        .link:hover {
            background-color: #1c2128;
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        
        .stats {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin: 20px 0;
        }
        
        .stat {
            text-align: center;
            padding: 15px;
            background-color: #21262d;
            border-radius: 10px;
            min-width: 100px;
        }
        
        .stat h3 {
            font-size: 1.8rem;
            margin: 0;
            color: #f78166;
        }
        
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .project {
            background-color: #21262d;
            border: 1px solid #30363d;
            border-radius: 10px;
            padding: 20px;
            transition: transform 0.3s ease;
        }
        
        .project:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }
        
        .project h3 {
            color: #58a6ff;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .project-languages {
            display: flex;
            gap: 10px;
            margin-top: 15px;
            flex-wrap: wrap;
        }
        
        .language {
            font-size: 0.8rem;
            color: #8b949e;
            padding: 4px 10px;
            background-color: #0d1117;
            border-radius: 15px;
        }
        
        footer {
            text-align: center;
            margin-top: 30px;
            color: #8b949e;
            font-size: 0.9rem;
        }
        
        .art-showcase {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }
        
        .art-item {
            height: 150px;
            background: linear-gradient(135deg, #21262d 0%, #30363d 100%);
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #8b949e;
            font-size: 3rem;
        }
        
        @media (max-width: 600px) {
            .stats {
                flex-direction: column;
                gap: 10px;
            }
            
            .links {
                flex-direction: column;
                align-items: center;
                gap: 10px;
            }
            
            h1 {
                font-size: 2rem;
            }
        }
        
        .quote {
            font-style: italic;
            text-align: center;
            padding: 15px;
            border-left: 3px solid #f78166;
            background-color: #21262d;
            border-radius: 0 10px 10px 0;
            margin: 20px 0;
        }
        
        .icon-header {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 15px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>👋 Hi there, I'm Shravani!</h1>
            <p>AI Student | Artist | Designer</p>
        </header>
        
        <div class="links">
            <a href="#" class="link">
                <i class="fas fa-envelope"></i> Email
            </a>
            <a href="#" class="link">
                <i class="fab fa-linkedin"></i> LinkedIn
            </a>
            <a href="https://instagram.com/sniffndraw" class="link">
                <i class="fab fa-instagram"></i> @sniffndraw
            </a>
            <a href="#" class="link">
                <i class="fas fa-paint-brush"></i> Art Portfolio
            </a>
        </div>
        
        <div class="stats">
            <div class="stat">
                <h3>5+</h3>
                <p>Programming Languages</p>
            </div>
            <div class="stat">
                <h3>4+</h3>
                <p>Design Tools</p>
            </div>
            <div class="stat">
                <h3>3+</h3>
                <p>Art Mediums</p>
            </div>
        </div>
    </div>
    
    <div class="container">
        <div class="icon-header">
            <i class="fas fa-laptop-code"></i>
            <h2>Technologies & Tools</h2>
        </div>
        <div class="badges">
            <span class="badge"><i class="fab fa-python"></i> Python</span>
            <span class="badge">C/C++</span>
            <span class="badge"><i class="fab fa-html5"></i> HTML</span>
            <span class="badge"><i class="fab fa-css3-alt"></i> CSS</span>
            <span class="badge"><i class="fas fa-database"></i> SQL</span>
            <span class="badge"><i class="fab fa-git-alt"></i> Git</span>
        </div>
    </div>
    
    <div class="container">
        <div class="icon-header">
            <i class="fas fa-paint-brush"></i>
            <h2>Design & Art Tools</h2>
        </div>
        <div class="badges">
            <span class="badge badge-design"><i class="fas fa-pencil-alt"></i> Photoshop</span>
            <span class="badge badge-design"><i class="fas fa-vector-square"></i> Illustrator</span>
            <span class="badge badge-design"><i class="fas fa-pen-fancy"></i> Procreate</span>
            <span class="badge badge-design"><i class="fas fa-magic"></i> Figma</span>
            <span class="badge badge-design"><i class="fas fa-drafting-compass"></i> Gravit Designer</span>
            <span class="badge badge-art"><i class="fas fa-paint-brush"></i> Ibis Paint</span>
            <span class="badge badge-art"><i class="fas fa-palette"></i> Sketchbook</span>
        </div>
    </div>
    
    <div class="container">
        <div class="icon-header">
            <i class="fas fa-project-diagram"></i>
            <h2>Learning Journey</h2>
        </div>
        <p>I'm currently exploring various domains to find my passion:</p>
        <div class="projects">
            <div class="project">
                <h3><i class="fas fa-brain"></i> AI/Data Science</h3>
                <p>Studying machine learning algorithms, data analysis, and statistical modeling as part of my engineering curriculum.</p>
            </div>
            
            <div class="project">
                <h3><i class="fas fa-code"></i> Web Development</h3>
                <p>Learning frontend and backend technologies to build interactive and responsive web applications.</p>
            </div>
            
            <div class="project">
                <h3><i class="fas fa-paint-brush"></i> UI/UX Design</h3>
                <p>Exploring user interface design principles and creating visually appealing, user-friendly experiences.</p>
            </div>
        </div>
    </div>
    
    <div class="container">
        <div class="icon-header">
            <i class="fas fa-palette"></i>
            <h2>Art & Illustration</h2>
        </div>
        <p>As a self-taught artist, I enjoy expressing creativity through:</p>
        <div class="badges">
            <span class="badge badge-art">Digital Art</span>
            <span class="badge badge-art">Traditional Illustration</span>
            <span class="badge badge-art">Character Design</span>
            <span class="badge badge-art">Portraits</span>
        </div>
        
        <h3>My Art Software Expertise:</h3>
        <div class="project-languages">
            <span class="language">Procreate</span>
            <span class="language">Ibis Paint</span>
            <span class="language">Autodesk Sketchbook</span>
            <span class="language">Photoshop</span>
            <span class="language">Gravit Designer</span>
        </div>
        
        <div class="quote">
            "Art is not what you see, but what you make others see." - Edgar Degas
        </div>
    </div>
    
    <div class="container">
        <div class="icon-header">
            <i class="fas fa-rocket"></i>
            <h2>Current Goals</h2>
        </div>
        <ul>
            <li>Complete my AI/Data Science engineering degree</li>
            <li>Build a strong foundation in web development</li>
            <li>Develop my UI/UX design skills</li>
            <li>Create a portfolio of both technical and artistic projects</li>
            <li>Find the perfect intersection of technology and creativity</li>
        </ul>
    </div>
    
    <div class="container">
        <div class="icon-header">
            <i class="fas fa-envelope"></i>
            <h2>Let's Connect!</h2>
        </div>
        <p>Feel free to reach out if you want to collaborate on creative projects or just have a chat!</p>
        <p>Email: <span class="highlight">your.email@example.com</span></p>
        <p>Art Instagram: <span class="highlight">@sniffndraw</span></p>
        <p>LinkedIn: <span class="highlight">linkedin.com/in/yourprofile</span></p>
    </div>
    
    <footer>
        <p>Made with ❤️ by Shravani | Combining Code with Creativity</p>
    </footer>
</body>
</html>
