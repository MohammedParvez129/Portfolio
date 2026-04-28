# Ex01 Portfolio
## Date: 27-04-2026
## Name: Mohammed Parvez S

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
Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Parvez Portfolio - Home</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Mohammed Parvez S</h1>
    <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Hello, I'm Parvez</h2>
    <p>Aspiring Computer Science Engineer passionate about Web Development, UI/UX Design, Python, and IoT Automation.</p>
    <a href="about.html" class="btn">Know More</a>
</section>

<footer>
    <p>© 2026 Mohammed Parvez S</p>
</footer>

</body>
</html>
```

about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>About - Parvez Portfolio</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Mohammed Parvez S</h1>
    <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="content">
    <h2>About Me</h2>
    <p>I am currently pursuing B.E Computer Science and Engineering at Saveetha Engineering College with 8.5 CGPA.</p>

    <p>I aim to contribute strong technical skills in Python, software development, and automation while continuously learning and growing professionally.</p>

    <h3>Education</h3>
    <ul>
        <li>B.E CSE - Saveetha Engineering College (2023 - 2027)</li>
        <li>HSC & SSLC - Velammal Matric Hr. Sec. School (97%)</li>
    </ul>
</section>

<footer>
    <p>© 2026 Mohammed Parvez S</p>
</footer>

</body>
</html>
```

skills.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Skills - Parvez Portfolio</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Mohammed Parvez S</h1>
    <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="content">
    <h2>My Skills</h2>

    <h3>Programming</h3>
    <ul>
        <li>Python</li>
        <li>Java (Basic)</li>
        <li>C (Basic)</li>
    </ul>

    <h3>Design Tools</h3>
    <ul>
        <li>Figma</li>
        <li>Adobe XD</li>
        <li>Canva</li>
    </ul>

    <h3>Other Skills</h3>
    <ul>
        <li>Arduino</li>
        <li>GitHub</li>
        <li>SQL (Learning)</li>
        <li>Data Visualization</li>
    </ul>
</section>

<footer>
    <p>© 2026 Mohammed Parvez S</p>
</footer>

</body>
</html>
```

projects.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Projects - Parvez Portfolio</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Mohammed Parvez S</h1>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="skills.html">Skills</a>
        <a href="projects.html">Projects</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="content">
    <h2>My Projects</h2>

    <div class="project-box">
        <h3>E-Commerce Website Prototype</h3>
        <p>
        Developed a responsive e-commerce website prototype with a smooth checkout flow.
        Improved user experience and reduced estimated cart abandonment using Figma, Canva, and Prototyping tools.
        </p>
    </div>

    <div class="project-box">
        <h3>Smarter Last-Mile Logistics</h3>
        <p>
        Currently developing an intelligent robot delivery service using path calculation and obstacle avoidance.
        Helps reduce delivery time and manpower using automation tools, cloud database, and robotic vehicles.
        </p>
    </div>

</section>

<footer>
    <p>© 2026 Mohammed Parvez S</p>
</footer>

</body>
</html>
```

contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Contact - Parvez Portfolio</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Mohammed Parvez S</h1>
    <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="content">
    <h2>Contact Me</h2>
    <p>Email: zevrap129@gmail.com</p>
    <p>Phone: 9043593261</p>
    <p>LinkedIn: Mohammed Parvez S</p>
</section>

<footer>
    <p>© 2026 Mohammed Parvez S</p>
</footer>

</body>
</html>
```

sytle.css
```
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    /* Deep red to near-black diagonal gradient for a dramatic background */
    background: linear-gradient(135deg, #2b0000 0%, #3b0000 30%, #000000 100%);
    color: #eee;
    min-height:100vh;
    -webkit-font-smoothing:antialiased;
    -moz-osx-font-smoothing:grayscale;
}

header{
    background:transparent;
    color: #fff;
    padding:24px 20px;
    text-align:center;
    position:relative;
}

nav{
    margin-top:10px;
}

nav a{
    color: #ffd6d6;
    text-decoration:none;
    margin:0 15px;
    font-size:18px;
    transition: color 160ms ease;
}

nav a:hover{
    color:#ff8080;
}

.hero{
    text-align:center;
    padding:100px 20px;
    background: rgba(0,0,0,0.25);
    margin:30px auto;
    border-radius:12px;
    width:90%;
    max-width:1100px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.6), inset 0 1px 0 rgba(255,255,255,0.02);
}

.hero h2{
    font-size:48px;
    margin-bottom:18px;
    color: #fff6f6;
    letter-spacing: -0.5px;
}

.hero p{
    font-size:20px;
    margin-bottom:25px;
    color:#ffdede;
}

.btn{
    background: linear-gradient(90deg, #ff4d4d, #b30000);
    color:white;
    padding:12px 25px;
    text-decoration:none;
    border-radius:8px;
    display:inline-block;
    box-shadow: 0 6px 18px rgba(179,0,0,0.35);
    transition: transform 160ms ease, box-shadow 160ms ease;
}

.btn:hover{
    transform: translateY(-4px);
    box-shadow: 0 14px 30px rgba(179,0,0,0.45);
}

.content{
    width:80%;
    margin:auto;
    padding:50px 20px;
    background: rgba(0,0,0,0.35);
    border-radius:10px;
    color:#fff1f1;
}

.content h2{
    margin-bottom:20px;
    color:#ffdede;
}

.content h3{
    margin-top:20px;
    margin-bottom:10px;
}

.content ul{
    margin-left:20px;
    line-height:2;
}

footer{
    background:transparent;
    color:#ffdede;
    text-align:center;
    padding:20px;
    margin-top:30px;
    border-top: 1px solid rgba(255,255,255,0.03);
}
```

## OUTPUT
<img width="1919" height="835" alt="image" src="https://github.com/user-attachments/assets/3c9b6293-7ece-44f5-b88c-52739da5d13d" />

<img width="1919" height="725" alt="image" src="https://github.com/user-attachments/assets/d0ed9c5b-5552-4d49-b9a1-4865fe5edc8e" />

<img width="1896" height="969" alt="image" src="https://github.com/user-attachments/assets/b16dd120-38e0-4318-871a-4dd85585bbbe" />

<img width="1918" height="715" alt="image" src="https://github.com/user-attachments/assets/2debb757-270f-4582-a01c-f66b2144fa9a" />

<img width="1919" height="575" alt="image" src="https://github.com/user-attachments/assets/bc613098-9d4b-4f90-9b94-4a75155e54d5" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
