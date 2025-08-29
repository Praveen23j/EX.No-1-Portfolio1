# Ex01 Portfolio
## Date:29.08.2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="2.css">
</head>
<body>

  <header>
    <div class="container">
      <h1>Praveen j</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="about">
    <div class="container">
      <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2025-08-29 160923.png" alt="Profile Picture">
      <h2>About Me</h2>
      <p>Hi! I’m praveen j, a passionate and dedicated college student currently pursuing btech at saveetha engineering college.
         I enjoy learning new technologies, developing projects, and exploring creative solutions. I’m eager to grow my skills in 
         [specific areas, e.g., web development, data analysis, or software engineering] 
        and contribute to meaningful projects. In my free time, I like participating in coding challenges, 
        working on personal projects, and collaborating with peers to bring ideas to life.</p>
    </div>
  </section>

  <section id="projects">
    <div class="container">
      <h2>My Projects</h2>
      <div class="projects-grid">
        <div class="project">
          <h3>Project 1</h3>
          <p>1. Personal Portfolio Website<br>
Created a responsive personal portfolio website using HTML, CSS, and JavaScript to showcase my projects, skills, and contact information..</p>
        </div>
        <div class="project">
          <h3>Project 2</h3>
          <p>2. To-Do List App<br>
Developed a web-based To-Do List application with JavaScript that allows users to add, edit, and delete tasks, enhancing productivity and task management..</p>
        </div>
        <div class="project">
          <h3>Project 3</h3>
          <p>3. College Event Management System<br>
Built a simple event management system using HTML, CSS, and basic JavaScript to help organize and track college events efficiently..</p>
        </div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" required></textarea>
        <button type="submit">Send</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 praveen j. All Rights Reserved.</p>
  </footer>

</body>
</html>

```
```

body {
  font-family: Arial, sans-serif;
  margin: 0;
  line-height: 1.6;
  background-color: #f5f5f5;
  color: #333;
}

.container {
  width: 80%;
  margin: auto;
  overflow: hidden;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
}

header h1 {
  display: inline-block;
  margin: 0;
}

header nav {
  float: right;
}

header nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

header nav ul li {
  display: inline;
  margin-left: 20px;
}

header nav ul li a {
  color: #fff;
  text-decoration: none;
}

section {
  padding: 40px 0;
  background-color: #fff;
  margin-bottom: 10px;
}

section:nth-child(even) {
  background-color: #eaeaea;
}

section img {
  max-width: 150px;
  border-radius: 50%;
}

.projects-grid {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}

.project {
  background-color: #fff;
  padding: 20px;
  flex: 1 1 calc(33% - 20px);
  box-shadow: 0 0 5px rgba(0,0,0,0.1);
  text-align: center;
}

form input, form textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 10px;
}

form button {
  padding: 10px 20px;
  background-color: #333;
  color: #fff;
  border: none;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 20px;
  background-color: #333;
  color: #fff;
}

```

## OUTPUT
<img width="1892" height="998" alt="Screenshot 2025-08-29 161917" src="https://github.com/user-attachments/assets/f6f0d30d-cce1-4249-995a-6c5933066ef4" />
<img width="1919" height="857" alt="Screenshot 2025-08-29 161937" src="https://github.com/user-attachments/assets/c5ad0fa7-d49c-4596-8aba-3203b5b25053" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
