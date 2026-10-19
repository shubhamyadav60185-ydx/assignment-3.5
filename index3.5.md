1. Aim

To design and develop a personal portfolio website using HTML and CSS. The website presents personal information, education, skills, interests, projects, blog posts, useful links and contact details.

2. Objectives

To create a personal portfolio website.

To use semantic HTML elements.

To add a header with a name and logo.

To create a working navigation bar.

To display About Me, Skills, Interests, Projects and Blog sections.

To use images, hyperlinks and lists.

To create a footer with contact information.

To maintain clean, readable and properly indented code.

To test the website and upload the project to GitHub.

3. Software and Technologies Used

Visual Studio Code

HTML5

CSS3

Web Browser

Git and GitHub

Live Server Extension

4. Project Folder Structure

Create a folder named Assignment-3.5 and save the following files inside it.

Assignment-3.5/
│
├── index.html
├── style.css
└── README.md

5. Complete Source Code

File 1: index.html

Create a file named index.html and paste the following complete code.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <meta name="description"
          content="Personal portfolio website showcasing education, skills, interests, projects and blog posts.">

    <title>Shubham Yadav | Personal Portfolio</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Website Header -->
    <header id="home">
        <div class="container header-content">
            <a href="#home" class="logo" aria-label="Portfolio home">
                SY<span>.</span>
            </a>

            <div>
                <h1>Shubham Yadav</h1>
                <p>B.Tech CSE Student | Aspiring Web Developer</p>
            </div>
        </div>
    </header>

    <!-- Navigation Bar -->
    <nav aria-label="Main navigation">
        <div class="container">
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#interests">Interests</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#links">Useful Links</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Main Website Content -->
    <main class="container">

        <!-- Introduction Section -->
        <section class="hero" aria-labelledby="hero-heading">
            <div class="hero-text">
                <p class="eyebrow">WELCOME TO MY PORTFOLIO</p>

                <h2 id="hero-heading">
                    Hello, I'm Shubham Yadav!
                </h2>

                <p>
                    I am a Computer Science and Engineering student
                    interested in programming, web development and
                    technology. I enjoy learning new skills and
                    creating useful projects.
                </p>

                <a class="button" href="#projects">
                    Explore My Projects
                </a>
            </div>

            <img
                class="profile-image"
                src="https://placehold.co/350x350/173b67/ffffff?text=Shubham+Yadav"
                alt="Placeholder profile illustration for Shubham Yadav"
                width="350"
                height="350"
            >
        </section>

        <!-- About Me Section -->
        <section id="about" class="content-section"
                 aria-labelledby="about-heading">

            <h2 id="about-heading">About Me</h2>

            <p>
                My name is Shubham Yadav. I am pursuing a Bachelor
                of Technology in Computer Science and Engineering
                at Invertis University.
            </p>

            <p>
                I am interested in learning programming, developing
                websites and understanding how modern technologies
                work. I believe that consistent practice and
                practical projects help improve technical skills.
            </p>

            <h3>My Education</h3>

            <ul class="detail-list">
                <li>
                    <strong>Current Course:</strong>
                    B.Tech in Computer Science and Engineering
                </li>

                <li>
                    <strong>University:</strong>
                    Invertis University
                </li>

                <li>
                    <strong>School Education:</strong>
                    Class 12, Lord Academy Secondary School
                </li>
            </ul>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="content-section"
                 aria-labelledby="skills-heading">

            <h2 id="skills-heading">My Skills</h2>

            <p>
                I am developing my technical knowledge through
                coursework, coding practice and personal projects.
            </p>

            <ul class="tag-list">
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript</li>
                <li>C Programming</li>
                <li>Web Development</li>
                <li>Problem Solving</li>
                <li>Teamwork</li>
                <li>Communication</li>
            </ul>
        </section>

        <!-- Interests Section -->
        <section id="interests" class="content-section"
                 aria-labelledby="interests-heading">

            <h2 id="interests-heading">My Interests</h2>

            <ul class="detail-list">
                <li>Learning new programming languages.</li>
                <li>Designing and developing websites.</li>
                <li>Exploring new technologies and tools.</li>
                <li>Participating in team projects and hackathons.</li>
                <li>Improving logical thinking and problem-solving.</li>
            </ul>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="content-section"
                 aria-labelledby="projects-heading">

            <h2 id="projects-heading">My Projects</h2>

            <p>
                The following project cards demonstrate how
                completed or ongoing projects can be presented
                in a personal portfolio.
            </p>

            <div class="card-grid">

                <article class="project-card">
                    <img
                        src="https://placehold.co/600x300/173b67/ffffff?text=Portfolio+Website"
                        alt="Illustration representing a personal portfolio website"
                        width="600"
                        height="300"
                        loading="lazy"
                    >

                    <div class="card-content">
                        <h3>Personal Portfolio Website</h3>

                        <p>
                            A responsive website built using HTML
                            and CSS to display personal information,
                            skills, projects and contact details.
                        </p>

                        <p class="project-status">
                            Category: Web Development
                        </p>

                        <a href="#home">View Portfolio</a>
                    </div>
                </article>

                <article class="project-card">
                    <img
                        src="https://placehold.co/600x300/2463a6/ffffff?text=AirIndex+Dashboard"
                        alt="Illustration representing an environmental data dashboard"
                        width="600"
                        height="300"
                        loading="lazy"
                    >

                    <div class="card-content">
                        <h3>AirIndex Dashboard Concept</h3>

                        <p>
                            A project concept for presenting air
                            quality information and environmental
                            data through an understandable dashboard.
                        </p>

                        <p class="project-status">
                            Category: Data Visualization
                        </p>

                        <a href="#contact">Project Information</a>
                    </div>
                </article>

                <article class="project-card">
                    <img
                        src="https://placehold.co/600x300/347a68/ffffff?text=HTML+Practice"
                        alt="Illustration representing HTML coding practice"
                        width="600"
                        height="300"
                        loading="lazy"
                    >

                    <div class="card-content">
                        <h3>HTML Practice Pages</h3>

                        <p>
                            Practice webpages demonstrating headings,
                            paragraphs, lists, hyperlinks, images
                            and semantic HTML elements.
                        </p>

                        <p class="project-status">
                            Category: HTML Fundamentals
                        </p>

                        <a href="#blog">Read Related Blog Posts</a>
                    </div>
                </article>

            </div>
        </section>

        <!-- Blog Section -->
        <section id="blog" class="content-section"
                 aria-labelledby="blog-heading">

            <h2 id="blog-heading">My Blog</h2>

            <div class="blog-grid">

                <article class="blog-card">
                    <p class="eyebrow">WEB DEVELOPMENT</p>

                    <h3>Why I Am Learning Web Development</h3>

                    <p>
                        Web development helps us create websites
                        and interactive online experiences. I am
                        starting with HTML and CSS before progressing
                        to JavaScript and more advanced technologies.
                    </p>

                    <a href="https://developer.mozilla.org/"
                       target="_blank"
                       rel="noopener noreferrer">
                        Explore Web Development
                    </a>
                </article>

                <article class="blog-card">
                    <p class="eyebrow">LEARNING</p>

                    <h3>The Importance of Regular Practice</h3>

                    <p>
                        Consistent practice helps students understand
                        programming concepts, identify errors and
                        develop problem-solving skills. Small projects
                        provide a practical way to learn.
                    </p>

                    <a href="https://www.freecodecamp.org/"
                       target="_blank"
                       rel="noopener noreferrer">
                        Find Learning Resources
                    </a>
                </article>

                <article class="blog-card">
                    <p class="eyebrow">STUDENT LIFE</p>

                    <h3>My Goals as a CSE Student</h3>

                    <p>
                        My goals are to strengthen programming
                        fundamentals, learn full-stack development,
                        build useful projects and collaborate
                        with other students.
                    </p>

                    <a href="https://github.com/"
                       target="_blank"
                       rel="noopener noreferrer">
                        Explore GitHub
                    </a>
                </article>

            </div>
        </section>

        <!-- Useful Links Section -->
        <section id="links" class="content-section"
                 aria-labelledby="links-heading">

            <h2 id="links-heading">Useful Links</h2>

            <p>
                These websites provide useful documentation,
                tutorials and tools for learning programming.
            </p>

            <ul class="detail-list">
                <li>
                    <a href="https://developer.mozilla.org/"
                       target="_blank"
                       rel="noopener noreferrer">
                        MDN Web Docs
                    </a>
                    — Documentation for HTML, CSS and JavaScript.
                </li>

                <li>
                    <a href="https://www.w3schools.com/"
                       target="_blank"
                       rel="noopener noreferrer">
                        W3Schools
                    </a>
                    — Beginner-friendly programming tutorials.
                </li>

                <li>
                    <a href="https://github.com/"
                       target="_blank"
                       rel="noopener noreferrer">
                        GitHub
                    </a>
                    — A platform for hosting and sharing code.
                </li>

                <li>
                    <a href="https://www.freecodecamp.org/"
                       target="_blank"
                       rel="noopener noreferrer">
                        freeCodeCamp
                    </a>
                    — Programming lessons and practical exercises.
                </li>
            </ul>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="content-section"
                 aria-labelledby="contact-heading">

            <h2 id="contact-heading">Contact Me</h2>

            <p>
                Thank you for visiting my portfolio. I am interested
                in learning new technologies and working on useful
                projects with other students.
            </p>

            <ul class="detail-list">
                <li>
                    <strong>Name:</strong> Shubham Yadav
                </li>

                <li>
                    <strong>Course:</strong> B.Tech CSE
                </li>

                <li>
                    <strong>University:</strong> Invertis University
                </li>

                <li>
                    <strong>GitHub:</strong>
                    <a href="https://github.com/"
                       target="_blank"
                       rel="noopener noreferrer">
                        Visit GitHub
                    </a>
                </li>
            </ul>

            <p>
                <strong>Email:</strong>
                Add your own email address before publishing.
            </p>
        </section>

    </main>

    <!-- Website Footer -->
    <footer>
        <div class="container">
            <p>
                &copy; 2026 Shubham Yadav.
                All rights reserved.
            </p>

            <p>
                Personal Portfolio | B.Tech CSE Student
            </p>

            <p>
                <a href="#home">Back to Top</a>
            </p>
        </div>
    </footer>

</body>
</html>

File 2: style.css

Create a second file named style.css in the same folder and paste this complete CSS code.

/* General Styling */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.7;
    background-color: #f4f7fb;
    color: #263238;
}

img {
    max-width: 100%;
    height: auto;
    display: block;
}

a {
    color: #175a9c;
}

a:focus {
    outline: 3px solid #f0a500;
    outline-offset: 3px;
}

.container {
    width: 90%;
    max-width: 1100px;
    margin: 0 auto;
}

/* Header */
header {
    background: linear-gradient(135deg, #102a43, #2563a6);
    color: white;
    padding: 25px 0;
}

.header-content {
    display: flex;
    align-items: center;
    gap: 20px;
}

.logo {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    min-width: 65px;
    height: 65px;
    background-color: white;
    color: #173b67;
    border-radius: 50%;
    font-size: 25px;
    font-weight: bold;
    text-decoration: none;
}

.logo span {
    color: #2563a6;
}

header h1 {
    font-size: 30px;
}

header p {
    color: #e1edfa;
}

/* Navigation */
nav {
    position: sticky;
    top: 0;
    z-index: 10;
    background-color: #163c65;
    padding: 14px 0;
}

.nav-links {
    list-style: none;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
}

.nav-links a {
    color: white;
    font-weight: bold;
    text-decoration: none;
}

.nav-links a:hover {
    color: #93c5fd;
    text-decoration: underline;
}

/* Main Content */
main {
    padding-top: 30px;
    padding-bottom: 30px;
}

section {
    scroll-margin-top: 100px;
}

.hero {
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 30px;
    background-color: white;
    padding: 35px;
    border-radius: 14px;
    margin-bottom: 30px;
    box-shadow: 0 4px 15px #00000010;
}

.hero-text {
    flex: 1 1 300px;
}

.hero h2 {
    color: #173b67;
    font-size: 35px;
    margin-bottom: 15px;
}

.hero p {
    margin-bottom: 15px;
}

.profile-image {
    width: 240px;
    border-radius: 12px;
}

.eyebrow {
    color: #2563a6;
    font-weight: bold;
    font-size: 13px;
    letter-spacing: 1px;
    margin-bottom: 8px;
}

.button {
    display: inline-block;
    background-color: #1d5fa7;
    color: white;
    padding: 10px 20px;
    border-radius: 6px;
    text-decoration: none;
    margin-top: 8px;
}

.button:hover {
    background-color: #123d70;
}

/* Content Sections */
.content-section {
    background-color: white;
    padding: 28px;
    border-radius: 12px;
    margin-bottom: 30px;
    box-shadow: 0 4px 15px #00000008;
}

.content-section h2 {
    color: #173b67;
    font-size: 28px;
    margin-bottom: 15px;
}

.content-section h3 {
    color: #20558a;
    margin: 12px 0;
}

.detail-list {
    padding-left: 24px;
    margin: 15px 0;
}

.detail-list li {
    margin-bottom: 8px;
}

.tag-list {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    list-style: none;
    margin-top: 18px;
}

.tag-list li {
    background-color: #e0edff;
    color: #163c65;
    padding: 8px 15px;
    border-radius: 20px;
    font-weight: bold;
}

/* Projects */
.card-grid,
.blog-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 22px;
    margin-top: 20px;
}

.project-card,
.blog-card {
    background-color: #ffffff;
    border: 1px solid #e0e7ef;
    border-radius: 10px;
    overflow: hidden;
}

.project-card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.card-content,
.blog-card {
    padding: 20px;
}

.card-content h3,
.blog-card h3 {
    color: #173b67;
    margin-bottom: 10px;
}

.card-content p,
.blog-card p {
    margin-bottom: 12px;
}

.project-status {
    color: #536779;
    font-size: 14px;
}

.card-content a,
.blog-card a {
    font-weight: bold;
}

.blog-card {
    background-color: #f9fbff;
}

/* Footer */
footer {
    background-color: #102a43;
    color: white;
    text-align: center;
    padding: 28px 15px;
}

footer p {
    margin-bottom: 8px;
}

footer a {
    color: #93c5fd;
}

footer a:hover {
    color: white;
}

/* Responsive Design */
@media (max-width: 700px) {
    .container {
        width: 92%;
    }

    .header-content {
        align-items: flex-start;
    }

    header h1 {
        font-size: 25px;
    }

    .nav-links {
        gap: 12px;
    }

    .hero {
        padding: 22px;
    }

    .hero h2 {
        font-size: 28px;
    }

    .profile-image {
        width: 190px;
    }

    .content-section {
        padding: 20px;
    }

    .content-section h2 {
        font-size: 24px;
    }
}

File 3: README.md

Create a third file named README.md and paste the following content.

# Personal Portfolio Website

## Project Description

This project is a personal portfolio website developed using
HTML5 and CSS3. It presents personal information, education,
skills, interests, projects, blog posts, useful links and
contact information.

## Features

- Personal header and logo
- Working navigation bar
- About Me section
- Skills and Interests sections
- Project cards with images
- Blog posts
- Useful external links
- Contact section and footer
- Responsive layout for mobile and desktop
- Semantic HTML elements

## Technologies Used

- HTML5
- CSS3
- Visual Studio Code
- Git and GitHub

## How to Run

1. Download or clone the repository.
2. Open the project folder in Visual Studio Code.
3. Open index.html using Live Server.
4. Browse the portfolio website.

## Author

Shubham Yadav

B.Tech Computer Science and Engineering

Invertis University

6. Explanation of the Website

Header with Name and Logo

The header displays the name, logo and professional introduction of the portfolio owner.

Navigation Bar

The navigation bar provides links to all major sections of the website. Each link uses an HTML ID to navigate to its corresponding section.

About Me

This section introduces the student and provides educational information.

Skills and Interests

The skills section displays technical and personal skills in an organized list. The interests section describes the areas the student wants to explore.

Projects

The projects section contains project cards with images, titles, descriptions and links.

Blog Posts

The blog section contains three sample articles about web development, consistent practice and goals as a Computer Science student.

Useful Links

The website provides links to MDN Web Docs, W3Schools, GitHub and freeCodeCamp.

Footer

The footer displays copyright information and a Back to Top link.

7. HTML Elements Used

HTML Element

Purpose

<header>

Displays the website introduction

<nav>

Contains navigation links

<main>

Contains the primary webpage content

<section>

Groups related content

<article>

Represents individual blog posts and projects

<footer>

Displays copyright and footer information

<h1>, <h2>, <h3>

Organize headings

<p>

Displays paragraphs

<ul> and <li>

Create lists

<a>

Creates hyperlinks

<img>

Displays images

8. Testing and Verification

The following checks should be performed:

Open index.html in a browser.

Verify that the CSS styling loads correctly.

Click every navigation link and confirm that it moves to the correct section.

Check that all project cards and blog posts are visible.

Verify that the images load correctly.

Test the layout on both desktop and mobile screen sizes.

Check external links.

Validate the HTML using the W3C Nu HTML Checker.

HTML validation website:

https://validator.w3.org/nu/

9. Screenshots

Capture screenshots of the actual running website.

Screenshot 1: Homepage and header.

Screenshot 2: About Me and Skills sections.

Screenshot 3: Projects and Blog sections.

Screenshot 4: Useful Links and Contact section.

Save the screenshots in a folder named screenshots if required by your instructor.

10. GitHub Repository Submission

Create a GitHub account or sign in to an existing account.

Create a public repository named Assignment-3.5.

Upload index.html, style.css and README.md.

Commit the uploaded files.

Open the repository page.

Copy the repository URL.

Submit the URL with the assignment.

Repository URL: Add your actual GitHub repository link after uploading the project.

GitHub: https://github.com/

11. Result

A personal blog and portfolio website was developed using HTML5 and CSS3. The website includes a header, navigation bar, About Me section, skills, interests, project cards, blog posts, images, useful links and a footer with contact information.

Semantic HTML elements were used to improve the structure and readability of the webpage. CSS was used to create a clean, attractive and responsive layout.

The project is ready for browser testing and GitHub submission after adding any required personal details and capturing the actual screenshots.


## 7. How to Run the Project

1. Open VS Code.
2. Create the folder `Assignment-3.5`.
3. Create all three files: `index.html`, `style.css` and `README.md`.
4. Paste each code block into its corresponding file.
5. Save all files using `Ctrl + S`.
6. Right-click `index.html` and select **Open with Live Server**.

## 8. GitHub Submission

After testing the project, upload all three files to a public GitHub repository named `Assignment-3.5`.

Repository link: `https://github.com/YOUR-USERNAME/Assignment-3.5`

Replace `YOUR-USERNAME` with your actual GitHub username after creating the repository.

**Important:** The website code is complete, but the repository link and screenshots must come from your actual GitHub account and running webpage. The images are placeholders, and you should replace them with your own images if required.