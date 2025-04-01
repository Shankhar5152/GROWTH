# GROWTH
I've enhanced My portfolio with advanced HTML, CSS, and JavaScript integration
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <script defer src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script defer src="script.js"></script>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">YEREY SHANKHAR</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="text-center p-5 bg-primary text-white">
        <h1>YEREY SHANKHAR</h1>
        <p>Web Developer | Software Engineer</p>
    </header>
    
    <section id="about" class="container py-5">
        <h2 class="text-center">About Me</h2>
        <p class="text-center">Hello! I am Yerey Shankhar, a passionate web developer with expertise in front-end and back-end development.</p>
    </section>
    
    <section id="skills" class="container py-5">
        <h2 class="text-center">Skills</h2>
        <div class="row text-center">
            <div class="col-md-3">HTML, CSS, JavaScript</div>
            <div class="col-md-3">React, Node.js</div>
            <div class="col-md-3">Python, Java</div>
            <div class="col-md-3">Database Management</div>
        </div>
    </section>
    
    <section id="projects" class="container py-5">
        <h2 class="text-center">Projects</h2>
        <div class="row">
            <div class="col-md-6">
                <div class="card">
                    <div class="card-body">
                        <h3 class="card-title">Project 1</h3>
                        <p class="card-text">Frontend Developer.</p>
                        <button class="btn btn-primary view-project">View More</button>
                    </div>
                </div>
            </div>
            <div class="col-md-6">
                <div class="card">
                    <div class="card-body">
                        <h3 class="card-title">Project 2</h3>
                        <p class="card-text">Inventory Management System</p>
                        <button class="btn btn-primary view-project">View More</button>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <section id="contact" class="container py-5">
        <h2 class="text-center">Contact Me</h2>
        <form id="contact-form" class="mx-auto w-50">
            <div class="mb-3">
                <input type="text" class="form-control" id="name" placeholder="Your Name" required>
            </div>
            <div class="mb-3">
                <input type="email" class="form-control" id="email" placeholder="Your Email" required>
            </div>
            <div class="mb-3">
                <textarea class="form-control" id="message" placeholder="Your Message" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send</button>
        </form>
        <p id="form-response" class="text-center mt-3"></p>
    </section>

    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2025 Yerey Shankhar. All rights reserved.</p>
    </footer>
</body>
</html>

