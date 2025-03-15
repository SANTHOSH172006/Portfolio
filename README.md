# Ex01 Portfolio
## Date: 14-03-2025

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
### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio - SANTHOSH D</title>
  <link rel="stylesheet" href="index.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Me</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="section"><br>
    <br>
    <h1><b>PORTFOLIO</b></h1>

    <h1>SANTHOSH D</h2>
    <h1>B.TECH IT, II Year</h3><br>
    <br>
    <h2>
      <p>
        I am SANTHOSH D, a second-year IT student pursuing a B.TECH degree. I am passionate about web development and java full-stack developer.
      </p>
    </h2>
    
  </section>

  <section id="about" class="section">
    <br><br>
    <h1>ABOUT ME</h1><br>
    <center>
    <h2>=> I am IT  student passionate about web development.</h2>
    <br>
    <h2>=> My interests include full-stack development.</h2>
    <br>
    <h2>=> My dream is to become a java full-stack developer.</h2>
    </center>
  </section>

  <section id="skills" class="section">
    <br><br>
    <h1>SKILLS</h1><br>
    <h1>Technical Skills</h1><br>
<h2>
  I) Programming:   C, Java, Python, SQL
</h2>
<h2>
 II) Web Development:   HTML, CSS, JavaScript
</h2>
<h2>
 III) Machine Learning:   Data Science, Algorithms
</h2>
<br>

    <br>
    <h1>Soft Skills</h1><br>
    <h2>I) Communication</h2>
    <h2>II) Project management</h2>
    <h2>III) Probelm-Solving</h2>
    
</section>

  

  <section id="contact" class="section">
    <br><br>
    <center>
    <h2>CONTACT ME</h2><br><br>
    <p>Email: dsanthosh17@gmail.com</p>
    <p>LinkedIn: <a href="#">https://www.linkedin.com/in/santhosh172006</a></p>
    <p>GitHub: <a href="#">https://github.com/SANTHOSH172006</a></p><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
        </center>

  <footer>
    <p>&copy; 2025 My Portfolio. All rights reserved.</p>
  </footer>
</section>
  
</body>
</html>
```
### index.css
```

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    scroll-behavior: smooth;
  }

  table {
          width: 70%;
          margin: auto;
          border-collapse: collapse;
      }
  th, td {
          border: 1px solid black;
          padding: 10px;
          text-align: center;
      }
  th {
          background-color: #f2f2f2;
      }

  nav {
    background-color: #333;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 100;
  }

  nav ul {
    list-style-type: none;
    text-align: center;
  }

  nav ul li {
    display: inline;
    margin: 0 20px;
  }

  nav a {
    text-decoration: none;
    color: white;
    font-weight: bold;
  }

  nav a:hover {
    color: red;
  }

  .section {
    padding: 50px 20px;
    min-height: 100vh;
    text-align: center;
  }

  #home {
    background-color: palevioletred;
  }

  #about {
    background-color: cyan;
  }

  #skills {
    background-color: skyblue;
  }

  #projects {
    background-color: #fff1b8;
  }

  #contact {
    background-color: red;
  }

  footer {
    background-color: black;
    color: white;
    text-align: center;
    padding: 10px 0;
  }

  .profile-photo {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-top: 20px;
  }

```

## OUTPUT
![HOME](https://github.com/user-attachments/assets/e0c3fffb-bb54-4528-83d6-10bf087dfd7c)
![ME](https://github.com/user-attachments/assets/d9a0faee-cdc9-49b4-a737-eab6023dff7d)
![SKILLS](https://github.com/user-attachments/assets/ec531f43-c38d-4722-aa66-cfb9cbbd8cce)
![CONTACT](https://github.com/user-attachments/assets/dbf94b74-4d55-4a71-8ae4-a5cd697f6f76)



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
