# portfolio_website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<style>
    body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
   
    
}

header {
    background: black;
    color: #fff;
    padding: 10px 0;
    text-align: center;
    
   
}

nav ul {
    list-style: none;
    padding: 0;
    
}

nav ul li {
    display: inline;
    margin: 0 15px;
    
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    background-color: blue;
}

section {
    padding: 20px;
    margin: 20px 0;
    
   
    
}


.project {
    border: 1px solid #ddd;
    padding: 10px;
    margin: 10px 0;
    color:coral;
    background-color: grey;
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #333;
    color: #fff;
    background-color:black;
}
</style>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! My name is Aryan Chaudhary ,I am a student of B.tech of 
            lovely Professional University. I am studying computer science and i want to became a web developer,app developer and game developer.
           I am currently studying Python , HTML,CSS,Java script as my coding language in my first semester.
           Side by side i am studying c++ to be a good coder and get a job in a good mnc(multi national company) and intership.
           I also wants to share my personal things like my hobbies , experinces , etc.
           My hobbies are to learn new technology , reading  books 
           And as per my experince the first thing a coder need to get a good job is to work hard on his or her coding practice and on DSA as in top mnc's company they always ask questions related to DSA.
           I am also active on some sites like Linkedin , quora, hacker rank , i am providing links which shows my profile on some websites:--<br>
           <a href="https://www.linkedin.com/in/aryan-chaudhary-9aa4a0306/?trk=opento_sprofile_details"><ul><li>linkedIn profile of mine</li></ul></a>
           <a href="https://www.quora.com/profile/Aryan-Chaudhary-938"><ul><li>Quora profile of mine.</li></ul></a>
           <a href="https://www.hackerrank.com/profile/ARYANCHAUDHARY62"><ul><li>Hacker Rank profile of mine.</li></ul></a><br>
           <img src="aryan.jpg" alt="Image" style="width:500px;height: 500px;"><br> ARYAN CHAUDHARY 
           </p>
           <div class=""></div> 
    </section>
 <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project </h3>
            <p>Description of project .</p>
            <a href="https://wordpress.com/post/knowledgeadda17.wordpress.com/4"><ul><li>My First project (Blog)</li></ul></a>
        </div>
       
        <!-- Add more projects as needed -->
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form id="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
