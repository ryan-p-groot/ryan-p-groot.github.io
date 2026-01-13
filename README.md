<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="logo">Your Name</div>
            <ul class="nav-menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
            <p class="hero-subtitle">Full Stack Developer | Creative Problem Solver</p>
            <div class="hero-buttons">
                <a href="#projects" class="btn btn-primary">View My Work</a>
                <a href="#contact" class="btn btn-secondary">Get In Touch</a>
            </div>
        </div>
        <div class="scroll-indicator">
            <i class="fas fa-chevron-down"></i>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>
                        I'm a passionate developer with a love for creating innovative solutions 
                        and beautiful user experiences. With expertise in modern web technologies, 
                        I bring ideas to life through clean, efficient code.
                    </p>
                    <p>
                        When I'm not coding, you'll find me exploring new technologies, contributing 
                        to open-source projects, or sharing knowledge with the developer community.
                    </p>
                    <a href="your-resume.pdf" class="btn btn-primary" download>Download Resume</a>
                </div>
                <div class="about-image">
                    <div class="image-placeholder">
                        <i class="fas fa-user"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <h2 class="section-title">My Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <div class="project-image">
                        <div class="project-placeholder">
                            <i class="fas fa-laptop-code"></i>
                        </div>
                    </div>
                    <div class="project-content">
                        <h3>Project Title 1</h3>
                        <p>Brief description of your project. What technologies you used and what problem it solves.</p>
                        <div class="project-tech">
                            <span class="tech-tag">React</span>
                            <span class="tech-tag">Node.js</span>
                            <span class="tech-tag">MongoDB</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
                            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
                        </div>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-image">
                        <div class="project-placeholder">
                            <i class="fas fa-mobile-alt"></i>
                        </div>
                    </div>
                    <div class="project-content">
                        <h3>Project Title 2</h3>
                        <p>Brief description of your project. What technologies you used and what problem it solves.</p>
                        <div class="project-tech">
                            <span class="tech-tag">Python</span>
                            <span class="tech-tag">Django</span>
                            <span class="tech-tag">PostgreSQL</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
                            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
                        </div>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-image">
                        <div class="project-placeholder">
                            <i class="fas fa-chart-line"></i>
                        </div>
                    </div>
                    <div class="project-content">
                        <h3>Project Title 3</h3>
                        <p>Brief description of your project. What technologies you used and what problem it solves.</p>
                        <div class="project-tech">
                            <span class="tech-tag">Vue.js</span>
                            <span class="tech-tag">Express</span>
                            <span class="tech-tag">MySQL</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
                            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <h2 class="section-title">Skills & Technologies</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3><i class="fas fa-code"></i> Frontend</h3>
                    <div class="skill-list">
                        <span class="skill-item">HTML5</span>
                        <span class="skill-item">CSS3</span>
                        <span class="skill-item">JavaScript</span>
                        <span class="skill-item">React</span>
                        <span class="skill-item">Vue.js</span>
                        <span class="skill-item">TypeScript</span>
                    </div>
                </div>
                <div class="skill-category">
                    <h3><i class="fas fa-server"></i> Backend</h3>
                    <div class="skill-list">
                        <span class="skill-item">Node.js</span>
                        <span class="skill-item">Python</span>
                        <span class="skill-item">Express</span>
                        <span class="skill-item">Django</span>
                        <span class="skill-item">REST APIs</span>
                        <span class="skill-item">GraphQL</span>
                    </div>
                </div>
                <div class="skill-category">
                    <h3><i class="fas fa-database"></i> Database</h3>
                    <div class="skill-list">
                        <span class="skill-item">MySQL</span>
                        <span class="skill-item">PostgreSQL</span>
                        <span class="skill-item">MongoDB</span>
                        <span class="skill-item">Redis</span>
                    </div>
                </div>
                <div class="skill-category">
                    <h3><i class="fas fa-tools"></i> Tools & Others</h3>
                    <div class="skill-list">
                        <span class="skill-item">Git</span>
                        <span class="skill-item">Docker</span>
                        <span class="skill-item">AWS</span>
                        <span class="skill-item">Linux</span>
                        <span class="skill-item">CI/CD</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <p class="contact-description">
                I'm always open to discussing new projects, creative ideas, or opportunities to be part of your visions.
            </p>
            <div class="contact-links">
                <a href="mailto:your.email@example.com" class="contact-link">
                    <i class="fas fa-envelope"></i>
                    <span>Email</span>
                </a>
                <a href="https://github.com/yourusername" class="contact-link" target="_blank">
                    <i class="fab fa-github"></i>
                    <span>GitHub</span>
                </a>
                <a href="https://linkedin.com/in/yourusername" class="contact-link" target="_blank">
                    <i class="fab fa-linkedin"></i>
                    <span>LinkedIn</span>
                </a>
                <a href="https://twitter.com/yourusername" class="contact-link" target="_blank">
                    <i class="fab fa-twitter"></i>
                    <span>Twitter</span>
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Your Name. All rights reserved.</p>
            <p>Built with ❤️ using HTML, CSS, and JavaScript</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>

/* Reset and Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --text-dark: #1f2937;
    --text-light: #6b7280;
    --bg-light: #f9fafb;
    --bg-white: #ffffff;
    --shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    --shadow-hover: 0 15px 40px rgba(0, 0, 0, 0.15);
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: var(--text-dark);
    background-color: var(--bg-white);
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Navigation */
.navbar {
    position: fixed;
    top: 0;
    width: 100%;
    background: rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(10px);
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    z-index: 1000;
    transition: all 0.3s ease;
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 1rem 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.nav-menu {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-menu a {
    text-decoration: none;
    color: var(--text-dark);
    font-weight: 500;
    transition: color 0.3s ease;
    position: relative;
}

.nav-menu a::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 0;
    height: 2px;
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    transition: width 0.3s ease;
}

.nav-menu a:hover::after,
.nav-menu a:focus::after {
    width: 100%;
}

.hamburger {
    display: none;
    flex-direction: column;
    cursor: pointer;
    gap: 4px;
}

.hamburger span {
    width: 25px;
    height: 3px;
    background: var(--text-dark);
    transition: all 0.3s ease;
}

/* Hero Section */
.hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 100px 20px 50px;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    position: relative;
}

.hero-content {
    max-width: 800px;
    animation: fadeInUp 1s ease;
}

.hero-title {
    font-size: 3.5rem;
    margin-bottom: 1rem;
    font-weight: 700;
}

.highlight {
    background: linear-gradient(135deg, #ffd89b 0%, #19547b 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.hero-subtitle {
    font-size: 1.5rem;
    margin-bottom: 2rem;
    opacity: 0.9;
}

.hero-buttons {
    display: flex;
    gap: 1rem;
    justify-content: center;
    flex-wrap: wrap;
}

.btn {
    padding: 12px 30px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: 600;
    transition: all 0.3s ease;
    display: inline-block;
    border: 2px solid transparent;
}

.btn-primary {
    background: white;
    color: var(--primary-color);
}

.btn-primary:hover {
    transform: translateY(-3px);
    box-shadow: var(--shadow-hover);
}

.btn-secondary {
    background: transparent;
    color: white;
    border: 2px solid white;
}

.btn-secondary:hover {
    background: white;
    color: var(--primary-color);
}

.scroll-indicator {
    position: absolute;
    bottom: 30px;
    animation: bounce 2s infinite;
}

.scroll-indicator i {
    font-size: 2rem;
    opacity: 0.7;
}

/* Section Styles */
section {
    padding: 80px 0;
}

.section-title {
    font-size: 2.5rem;
    text-align: center;
    margin-bottom: 3rem;
    position: relative;
    display: inline-block;
    width: 100%;
}

.section-title::after {
    content: '';
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
    width: 80px;
    height: 4px;
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    border-radius: 2px;
}

/* About Section */
.about {
    background: var(--bg-light);
}

.about-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
    align-items: center;
}

.about-text p {
    margin-bottom: 1.5rem;
    font-size: 1.1rem;
    color: var(--text-light);
    line-height: 1.8;
}

.image-placeholder {
    width: 100%;
    aspect-ratio: 1;
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    border-radius: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: var(--shadow);
}

.image-placeholder i {
    font-size: 8rem;
    color: white;
    opacity: 0.7;
}

/* Projects Section */
.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 2rem;
}

.project-card {
    background: var(--bg-white);
    border-radius: 15px;
    overflow: hidden;
    box-shadow: var(--shadow);
    transition: all 0.3s ease;
}

.project-card:hover {
    transform: translateY(-10px);
    box-shadow: var(--shadow-hover);
}

.project-image {
    height: 200px;
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
}

.project-placeholder {
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
}

.project-placeholder i {
    font-size: 4rem;
    color: white;
    opacity: 0.7;
}

.project-content {
    padding: 1.5rem;
}

.project-content h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
    color: var(--text-dark);
}

.project-content p {
    color: var(--text-light);
    margin-bottom: 1rem;
}

.project-tech {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-bottom: 1rem;
}

.tech-tag {
    background: var(--bg-light);
    padding: 0.3rem 0.8rem;
    border-radius: 20px;
    font-size: 0.85rem;
    color: var(--text-dark);
}

.project-links {
    display: flex;
    gap: 1rem;
}

.project-link {
    color: var(--primary-color);
    text-decoration: none;
    font-weight: 600;
    display: flex;
    align-items: center;
    gap: 0.5rem;
    transition: color 0.3s ease;
}

.project-link:hover {
    color: var(--secondary-color);
}

/* Skills Section */
.skills {
    background: var(--bg-light);
}

.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
}

.skill-category {
    background: var(--bg-white);
    padding: 2rem;
    border-radius: 15px;
    box-shadow: var(--shadow);
}

.skill-category h3 {
    font-size: 1.3rem;
    margin-bottom: 1.5rem;
    color: var(--text-dark);
    display: flex;
    align-items: center;
    gap: 0.5rem;
}

.skill-category h3 i {
    color: var(--primary-color);
}

.skill-list {
    display: flex;
    flex-direction: column;
    gap: 0.8rem;
}

.skill-item {
    padding: 0.7rem 1rem;
    background: var(--bg-light);
    border-radius: 8px;
    text-align: center;
    font-weight: 500;
    color: var(--text-dark);
    transition: all 0.3s ease;
}

.skill-item:hover {
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    color: white;
    transform: translateX(5px);
}

/* Contact Section */
.contact {
    text-align: center;
}

.contact-description {
    font-size: 1.1rem;
    color: var(--text-light);
    margin-bottom: 3rem;
    max-width: 600px;
    margin-left: auto;
    margin-right: auto;
}

.contact-links {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 2rem;
}

.contact-link {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0.5rem;
    text-decoration: none;
    color: var(--text-dark);
    padding: 2rem;
    border-radius: 15px;
    background: var(--bg-light);
    min-width: 150px;
    transition: all 0.3s ease;
    box-shadow: var(--shadow);
}

.contact-link:hover {
    transform: translateY(-5px);
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    color: white;
    box-shadow: var(--shadow-hover);
}

.contact-link i {
    font-size: 2.5rem;
}

.contact-link span {
    font-weight: 600;
    font-size: 1.1rem;
}

/* Footer */
.footer {
    background: var(--text-dark);
    color: white;
    text-align: center;
    padding: 2rem 0;
}

.footer p {
    margin: 0.5rem 0;
}

/* Animations */
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes bounce {
    0%, 20%, 50%, 80%, 100% {
        transform: translateY(0);
    }
    40% {
        transform: translateY(-10px);
    }
    60% {
        transform: translateY(-5px);
    }
}

/* Responsive Design */
@media (max-width: 768px) {
    .nav-menu {
        position: fixed;
        left: -100%;
        top: 70px;
        flex-direction: column;
        background: white;
        width: 100%;
        text-align: center;
        transition: 0.3s;
        box-shadow: 0 10px 27px rgba(0, 0, 0, 0.05);
        padding: 2rem 0;
    }

    .nav-menu.active {
        left: 0;
    }

    .hamburger {
        display: flex;
    }

    .hamburger.active span:nth-child(1) {
        transform: rotate(45deg) translate(5px, 5px);
    }

    .hamburger.active span:nth-child(2) {
        opacity: 0;
    }

    .hamburger.active span:nth-child(3) {
        transform: rotate(-45deg) translate(7px, -6px);
    }

    .hero-title {
        font-size: 2.5rem;
    }

    .hero-subtitle {
        font-size: 1.2rem;
    }

    .about-content {
        grid-template-columns: 1fr;
    }

    .projects-grid {
        grid-template-columns: 1fr;
    }

    .skills-grid {
        grid-template-columns: 1fr;
    }

    .contact-links {
        flex-direction: column;
        align-items: center;
    }
}

// Mobile Menu Toggle
const hamburger = document.querySelector('.hamburger');
const navMenu = document.querySelector('.nav-menu');

hamburger.addEventListener('click', () => {
    hamburger.classList.toggle('active');
    navMenu.classList.toggle('active');
});

// Close mobile menu when clicking on a link
document.querySelectorAll('.nav-menu a').forEach(link => {
    link.addEventListener('click', () => {
        hamburger.classList.remove('active');
        navMenu.classList.remove('active');
    });
});

// Smooth scroll for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            target.scrollIntoView({
                behavior: 'smooth',
                block: 'start'
            });
        }
    });
});

// Navbar background on scroll
window.addEventListener('scroll', () => {
    const navbar = document.querySelector('.navbar');
    if (window.scrollY > 50) {
        navbar.style.background = 'rgba(255, 255, 255, 0.98)';
        navbar.style.boxShadow = '0 2px 20px rgba(0, 0, 0, 0.1)';
    } else {
        navbar.style.background = 'rgba(255, 255, 255, 0.95)';
        navbar.style.boxShadow = '0 2px 10px rgba(0, 0, 0, 0.1)';
    }
});

// Intersection Observer for fade-in animations
const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -100px 0px'
};

const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.style.opacity = '1';
            entry.target.style.transform = 'translateY(0)';
        }
    });
}, observerOptions);

// Observe project cards and skill categories
document.querySelectorAll('.project-card, .skill-category').forEach(el => {
    el.style.opacity = '0';
    el.style.transform = 'translateY(30px)';
    el.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
    observer.observe(el);
});
