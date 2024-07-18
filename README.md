# html-city-tourism
# Ex-1
Aim: Create the website of the tourism sites of your desired city 
Code:
```
<!DOCTYPE html>
<html>
<head>
<title>My Day</title>
</head>
<body>
<table cellpadding= "10" cellspacing="10" style="border-style: double;">
<tr>
<th colspan="2" class="center" style="border-style: double;"><mark>My Day</mark></th>
</tr>
<tr>
<td style="border-style: double;">
<ol>
<li>wake up early
<ul>
<li style="list-style-type: square; margin-bottom: 20px">5AM</li>
<li>walk</li>
<li>jog</li>
</ul>
</li>
</ol>
</td>
<td rowspan="3" style="border-style: double;">
<table>
<tr>
<th colspan="2" class="center highlight" style="border-style: double;"><mark>Things to watch</mark></th>
</tr>
<tr >
<td style="border-style: double;"><img src="sun.jpeg" alt="image 1" width="100" height="100" >
<td style="border-style: double;"><img src="dosa.jpg" alt="image 2" width="100" height="100">
</tr>
<tr>
<td style="border-style: double;"><img src="coffee.jpg" alt="image 3" width="100" height="100">
<td style="border-style: double;"><img src="teaching.jpg" alt="image 4" width="100" height="100">
</td>
</tr>
<tr>
<td></td>
</tr>
</table>
</td>
</tr>
<tr>
<td style="border-style: double;">
<ol start="2">
<li>breakfast
<ul>
<li style="list-style-type: square; margin-bottom: 20px">8AM</li>
<li>eggs</li>
<li>coffee</li>
</ul>
</li>
</ol>
</td>
</tr>
<tr>
<td style="border-style: double;">
<ol start="3">
<li>go to Saveetha
<ul>
<li style="list-style-type: square; margin-bottom: 20px">8AM</li>
<li>attend classes</li>
<li>to be continued</li>
</ul>
</li>
</ol>
</td>
</tr>
</table>
</body>
</html>
```
# Output:

![Screenshot 2024-07-13 104104](https://github.com/user-attachments/assets/d9469aab-fd0b-4af2-88cd-ae99c190146a)

# Result:
Thus,Creating a html file to display the content in the above picture was executed successfully.

# Ex-2
Aim: Design a website for a College
Code:
# Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Name</title>
    <style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }
    
    header {
        background-color: orangered;
        color: #fff;
        padding: 1rem;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    
    header img {
        max-height: 50px;
    }
    
    nav ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
        display: flex;
    }
    
    nav ul li {
        margin: 0 1rem;
    }
    
    nav ul li a {
        color: #fff;
        text-decoration: none;
    }
    
    main {
        padding: 2rem;
    }
    
    footer {
        background-color:orangered;
        color: #fff;
        text-align: center;
        padding: 1rem;
        position: fixed;
        width: 100%;
        bottom: 0;
    }
    </style>
</head>
<body>
    <header>
        <img src="logo sav.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
    </header>
    <main>
        <h1>Saveetha Engineering College</h1>
        <p>Welcome to our college, where we offer a wide range of academic programs and extracurricular activities.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
# Academics.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academics - Saveetha Engineering College</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: orangered;
            color: #fff;
            padding: 1rem;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        header img {
            max-height: 50px;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        
        nav ul li {
            margin: 0 1rem;
        }
        
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        
        main {
            padding: 2rem;
        }
        
        footer {
            background-color:orangered;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        </style>
</head>
<body>
    <header>
        <img src="logo sav.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses/computer-science.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Academics</h1>
        <p>Explore our academic programs and research opportunities.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
# Admission.html
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission - College Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: orangered;
            color: #fff;
            padding: 1rem;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        header img {
            max-height: 50px;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        
        nav ul li {
            margin: 0 1rem;
        }
        
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        
        main {
            padding: 2rem;
        }
        
        footer {
            background-color:orangered;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        </style>
</head>
<body>
    <header>
        <img src="logo sav.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses/computer-science.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Admission</h1>
        <p>Learn about our admission process, requirements, and deadlines.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
# Gallery.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery - College Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: orangered;
            color: #fff;
            padding: 1rem;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        header img {
            max-height: 50px;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        
        nav ul li {
            margin: 0 1rem;
        }
        
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        
        main {
            padding: 1px;align-self: initial;
            height: auto;
            width: auto;
        }
        
        footer {
            background-color:orangered;
            color: #fff;
            text-align: center;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        * {
  box-sizing: border-box;
}

.row {
  display: flex;
}

/* Create three equal columns that sits next to each other */
.column {
  flex: 33.33%;
  padding: 5px;
}
        </style>
</head>
<body>
    <header>
        <img src="logo sav.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="courses/computer-science.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <h1>Gallery</h1>
    <p>Explore our campus and student life through these photos.</p>
    <div class="row">
        <div class="column">
          <img src="class room.png" alt="Snow" style="width:100%">
        </div>
        <div class="column">
          <img src="class.jpg" alt="Forest" style="width:100%">
        </div>
        <div class="column">
          <img src="arvr.png" alt="Mountains" style="width:100%">
        </div>
      </div>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
# Courses.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Courses Offered - College Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: orangered;
            color: #fff;
            padding: 1rem;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        header img {
            max-height: 50px;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        
        nav ul li {
            margin: 0 1rem;
        }
        
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        
        main {
            padding: 2rem;
        }
        
        footer {
            background-color:orangered;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        </style>
</head>
<body>
    <header>
        <img src="logo sav.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Courses Offered</h1>
        <p>We offer a diverse range of courses across multiple disciplines. Explore our course offerings below:</p>
        <ul>
            <li><a href="computer.html">Computer Science</a></li>
            <li><a href="mathematics.html">Mathematics</a></li>
            <li><a href="english.html">English</a></li>
            <li><a href="social.html">Sociology</a></li>
            <li><a href="economics.html">Economics</a></li>
            <li><a href="mangement.html">Business Management</a></li>
        </ul>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
# ComputerScience.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Computer Science - College Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: orangered;
            color: #fff;
            padding: 1rem;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        header img {
            max-height: 50px;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        
        nav ul li {
            margin: 0 1rem;
        }
        
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        
        main {
            padding: 2rem;
        }
        
        footer {
            background-color:orangered;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        </style>
</head>
<body>
    <header>
        <img src="logo sav.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Computer Science</h1>
        <p>Welcome to the Computer Science department. Here you can find information about our programs, faculty, and research opportunities.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
# Mathematics.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mathematics - College Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: orangered;
            color: #fff;
            padding: 1rem;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        header img {
            max-height: 50px;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        
        nav ul li {
            margin: 0 1rem;
        }
        
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        
        main {
            padding: 2rem;
        }
        
        footer {
            background-color:orangered;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        </style>
</head>
<body>
    <header>
        <img src="logo sav.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="../index.html">Home</a></li>
                <li><a href="../academics.html">Academics</a></li>
                <li><a href="../admission.html">Admission</a></li>
                <li><a href="../gallery.html">Gallery</a></li>
                <li><a href="../courses.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Mathematics</h1>
        <p>The Mathematics program at College Name offers a rigorous education in pure and applied mathematics. Our curriculum includes courses in calculus, linear algebra, differential equations, probability, and more.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Calculus I</li>
            <li>Calculus II</li>
            <li>Linear Algebra</li>
            <li>Differential Equations</li>
            <li>Probability and Statistics</li>
            <li>Abstract Algebra</li>
            <li>Real Analysis</li>
            <li>Numerical Methods</li>
        </ul>
        <h2>Faculty</h2>
        <p>Our faculty are leaders in mathematical research and education, committed to helping students succeed in their studies and careers.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
# English.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>English - College Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: orangered;
            color: #fff;
            padding: 1rem;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        header img {
            max-height: 50px;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        
        nav ul li {
            margin: 0 1rem;
        }
        
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        
        main {
            padding: 2rem;
        }
        
        footer {
            background-color:orangered;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        </style>
</head>
<body>
    <header>
        <img src="logo sav.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>English</h1>
        <p>The English program at College Name covers literature, writing, and critical thinking. Students will explore a wide range of literary works and develop strong analytical and communication skills.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Introduction to Literature</li>
            <li>Creative Writing</li>
            <li>Shakespearean Studies</li>
            <li>American Literature</li>
            <li>Modernist Literature</li>
            <li>Postcolonial Literature</li>
            <li>Literary Theory</li>
            <li>Advanced Composition</li>
        </ul>
        <h2>Faculty</h2>
        <p>Our faculty are accomplished writers and scholars, dedicated to fostering a love of literature and a mastery of writing in their students.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
# Social.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sociology - College Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: orangered;
            color: #fff;
            padding: 1rem;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        header img {
            max-height: 50px;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        
        nav ul li {
            margin: 0 1rem;
        }
        
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        
        main {
            padding: 2rem;
        }
        
        footer {
            background-color:orangered;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        </style>
</head>
<body>
    <header>
        <img src="logo sav.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Sociology</h1>
        <p>The Sociology program at College Name examines the structures of societies, groups, and organizations. Our courses cover topics such as social theory, research methods, and social issues.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Introduction to Sociology</li>
            <li>Social Theory</li>
            <li>Research Methods in Sociology</li>
            <li>Sociology of the Family</li>
            <li>Sociology of Education</li>
            <li>Sociology of Health</li>
            <li>Criminology</li>
            <li>Urban Sociology</li>
        </ul>
        <h2>Faculty</h2>
        <p>Our faculty members are experts in various fields of sociology, dedicated to advancing knowledge and solving social problems through research and teaching.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</head>
</html>
```
# Economics.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Economics - College Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: orangered;
            color: #fff;
            padding: 1rem;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        header img {
            max-height: 50px;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        
        nav ul li {
            margin: 0 1rem;
        }
        
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        
        main {
            padding: 2rem;
        }
        
        footer {
            background-color:orangered;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        </style>
</head>
<body>
    <header>
        <img src="logo sav.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Economics</h1>
        <p>The Economics program at College Name provides students with a solid foundation in economic theory, quantitative methods, and applied economics. Our curriculum prepares students for careers in business, government, and research.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Microeconomics</li>
            <li>Macroeconomics</li>
            <li>Econometrics</li>
            <li>Public Economics</li>
            <li>International Economics</li>
            <li>Development Economics</li>
            <li>Labor Economics</li>
            <li>Financial Economics</li>
        </ul>
        <h2>Faculty</h2>
        <p>Our faculty members are accomplished economists with expertise in various areas of economic research and policy analysis.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
# Management.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Business Management - College Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: orangered;
            color: #fff;
            padding: 1rem;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        header img {
            max-height: 50px;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        
        nav ul li {
            margin: 0 1rem;
        }
        
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        
        main {
            padding: 2rem;
        }
        
        footer {
            background-color:orangered;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        </style>
</head>
<body>
    <header>
        <img src="logo sav.png" alt="College Logo">
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="Courses.html">Courses</a></li>
            </ul>
    </header>
    <main>
        <h1>Business Management</h1>
        <p>The Business Management program at College Name equips students with the knowledge and skills needed to succeed in the business world. Our curriculum covers management principles, organizational behavior, finance, marketing, and more.</p>
        <h2>Course Structure</h2>
        <ul>
            <li>Principles of Management</li>
            <li>Organizational Behavior</li>
            <li>Financial Management</li>
            <li>Marketing Management</li>
            <li>Operations Management</li>
            <li>Human Resource Management</li>
            <li>Strategic Management</li>
            <li>Business Ethics</li>
        </ul>
        <h2>Faculty</h2>
        <p>Our faculty members are experienced business professionals and academics, dedicated to providing a comprehensive business education to our students.</p>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
# Output
![Screenshot 2024-07-14 211503](https://github.com/user-attachments/assets/7456cf1c-caf1-4f6f-90a8-d99db95d4a9e)

![Screenshot 2024-07-14 211525](https://github.com/user-attachments/assets/d44ec184-5ed2-4f7c-bd7b-8a1d0dec0ec9)

![Screenshot 2024-07-14 211607](https://github.com/user-attachments/assets/73352412-1052-4b74-a88d-353ffffd3148)

![Screenshot 2024-07-14 211712](https://github.com/user-attachments/assets/f6173a79-e4df-4249-a024-fedfb742c249)

![Screenshot 2024-07-14 212005](https://github.com/user-attachments/assets/f85adab7-3ceb-4443-ae46-1dd5855fbc4b)

![Screenshot 2024-07-14 212302](https://github.com/user-attachments/assets/80166793-e959-4b3c-af22-267df7357567)

![Screenshot 2024-07-14 214816](https://github.com/user-attachments/assets/fce7a818-b555-4b5c-a372-c707e89ad6f2)

![Screenshot 2024-07-14 212928](https://github.com/user-attachments/assets/9bb62f68-e1a3-4488-8d37-a5135e39f531)

![Screenshot 2024-07-14 213719](https://github.com/user-attachments/assets/f57be2ca-ff00-473a-a117-0a0ab43f368e)

![Screenshot 2024-07-14 214052](https://github.com/user-attachments/assets/da67ef1c-89fc-4f91-be4e-f4dd5d3e0cad)

![Screenshot 2024-07-14 214646](https://github.com/user-attachments/assets/020673bc-213d-4d94-8ec7-af62f9cbb0e8)
# Result:
Thus,Creating a website for college was executed successfully.

