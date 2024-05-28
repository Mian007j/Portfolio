<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: #333;
            color: #fff;
            padding: 2em 0;
            text-align: center;
        }
        section {
            padding: 2em 0;
        }
        section h2 {
            margin-top: 0;
            border-bottom: 2px solid #333;
            padding-bottom: 0.5em;
        }
        .container ul {
            list-style: none;
            padding: 0;
        }
        .container ul li {
            margin: 0.5em 0;
            padding: 0.5em;
            background: #f8f8f8;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        form button {
            background: #333;
            color: #fff;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        form button:hover {
            background: #555;
        }
    </style>
</head>
<body>
    
    <header>
        <div class="container">
            <h1>Muneeb Ahmad</h1>
            <h2>Johar Town Laahore</h2>
            <p> Title Line</p>
        </div>
    </header>

    
    <section id="education">
        <div class="container">
            <h2>Education</h2>
            <ul>
                <li><strong>Metric:</strong> The Educators</li>
                <li><strong>Intermediate:</strong> Punjab College</li>
                <li><strong>Bachelor of Science:</strong> University of Manahement and Technology</li>
            </ul>
        </div>
    </section>

    
    <section id="skills">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>Pyhton Programmer</li>
                <li>C++ Programmer</li>
                <li>3D game Developer</li>
            </ul>
        </div>
    </section>

   
    <section id="experience">
        <div class="container">
            <h2>Experience</h2>
            <ul>
                <li><strong>Job Title:</strong> Company Name</li>
                <li><strong>Job Title:</strong> Company Name</li>
            </ul>
        </div>
    </section>

    
    <section id="projects">
        <div class="container">
            <h2>Complete Projects</h2>
            <ul>
                <li><a href="link-to-project-1">Project 1</a></li>
                <li><a href="link-to-project-2">Project 2</a></li>
            </ul>
        </div>
    </section>

   
    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <form action="https://formspree.io/your-email" method="POST">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" class="form-control" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" class="form-control" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="message">Message:</label>
                    <textarea class="form-control" id="message" name="message" required></textarea>
                </div>
                <button type="submit" class="btn btn-dark">Send</button>
            </form>
        </div>
    </section>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
