# Ex01 Portfolio
## Date: 29-07-2026

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
## index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>PORTFOLIO</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</nav>

<section>
    <img src="profile.jpeg" width="200">
    <h2>Welcome</h2>
    <p>I am a B.E. CSE student with skills in Python, C, Java, HTML and CSS.</p>
</section>
<footer>
    <p>&copy; Darshini. All Rights Reserved.</p>
    
</footer>
</body>
</html>
```
## about.html
```
<!DOCTYPE html>
<html>
<head>
    <title>About</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>About Me</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</nav>

<section>
    <h2>About Me</h2>

    <p>
        I am passionate about programming and software development.
        I have knowledge of Python, C, Java, HTML and CSS.
        I enjoy solving coding problems and learning new technologies.
    </p>

</section>
<footer>
    <p>&copy; Darshini. All Rights Reserved.</p>
    
</footer>
</body>
</html>
```

## projects.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Projects</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>My Projects</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</nav>

<section>

<div class="card">
<h3>Portfolio Website</h3>
<p>Responsive website using HTML and CSS.</p>
</div>

<div class="card">
<h3>Student Management System</h3>
<p>Developed using C language.</p>
</div>

<div class="card">
<h3>Python Calculator</h3>
<p>Calculator developed using Python.</p>
</div>

</section>
<footer>
    <p>&copy; Darshini. All Rights Reserved.</p>
    
</footer>
</body>
</html>
```

## contact.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Contact Me</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</nav>

<section>

<h2>Contact Details</h2>

<p>Email : darshini.monish@gmail.com</p>

<p>GitHub : https://github.com/arshinimonish-tech</p>

</section>
<footer>
    <p>&copy; DARSHINI R. All Rights Reserved.</p>
</footer>
</body>
</html>
```

## style.css
```
body{
    font-family:Arial,sans-serif;
    margin:0;
    background:#f2f2f2;
}

header{
    background:#0066cc;
    color:white;
    padding:20px;
    text-align:center;
}

nav{
    background:#222;
    text-align:center;
    padding:15px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:20px;
    font-size:18px;
}

nav a:hover{
    color:yellow;
}

section{
    padding:30px;
    text-align:center;
}

img{
    border-radius:50%;
}

.card{
    width:250px;
    display:inline-block;
    margin:15px;
    padding:20px;
    background:white;
    box-shadow:0 0 10px gray;
    transition:0.4s;
}

.card:hover{
    background:#0066cc;
    color:white;
    transform:scale(1.05);
}
footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:250px;
}

footer p{
    margin:8px 0;
}

footer a{
    color:white;
    text-decoration:none;
    margin:0 10px;
    transition:0.3s;
}

footer a:hover{
    color:yellow;
}
```

## OUTPUT
<img width="957" height="576" alt="image" src="https://github.com/user-attachments/assets/67f522bf-c261-4e87-875b-6ffab1c61578" />
<img width="1086" height="500" alt="image" src="https://github.com/user-attachments/assets/4c5ded3a-0ad3-4a66-a9d1-7a5f20dbb2a2" />
<img width="1080" height="610" alt="image" src="https://github.com/user-attachments/assets/4bab7ecf-636a-4dd3-a771-2334c589bf02" />
