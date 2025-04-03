# Hackatho-1-FEB-2025<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jerim Owino - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        img {
            display: block;
            max-width: 100%;
            height: auto;
            margin: 20px auto;
            width: 500px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h2>About Me</h2>
        <p>My name is Jerim Owino. I am passionate about technology and innovation. I have successfully led and completed multiple projects, including a real-time chat application, a personal blog platform, and this portfolio website. My recent projects have received great feedback for their functionality and user experience.</p>
        <img src="https://example.com/biochemistry-image.jpg" alt="Biochemistry Lab">
        <img src="https://example.com/software-developer.jpg" alt="Young man coding on a computer">
    </section>
    
    <section id="education">
        <h2>Educational Background</h2>
        <p>BSc in Biochemistry and Molecular Biology | BED in Arts (Guidance & Counseling, English Literature) | Power Learn Project Software Development</p>
        <a href="Jerim_CV.docx" download>Download My CV</a>
    </section>
    
    <section id="skills">
        <h2>Programming Languages</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>Python</li>
        </ul>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <ul>
      
          <!-- New Projects with GitHub links -->
            <li><a href="https://github.com/jerim76/introduction-to-python-assignment.git" target="_blank">Introduction to Python Assignment</a> - A beginner-level Python assignment project.</li>
            <li><a href="https://github.com/jerim76/python-assign.git" target="_blank">Python Assignment</a> - A set of Python exercises demonstrating basic concepts.</li>
            <li><a href="https://github.com/jerim76/calcul.py.git" target="_blank">Calcul.py</a> - A Python calculator project with basic arithmetic operations.</li>
        </ul>
    </section>
    
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:owinojerim269@gmail.com">owinojerim269@gmail.com</a></p>
        <p>Phone: <a href="tel:+254758943430">+254758943430</a></p>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send</button>
        </form>
    </section>
</body>
</html>

