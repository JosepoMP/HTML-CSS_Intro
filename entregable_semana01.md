<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Portafolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&display=swap" rel="stylesheet">
</head>

<body style="font-family: 'DM Serif Display'; margin: 2cm; background-color:floralwhite; color: #333;">
    <!--Encabezado-->
    <h1 style="text-align: center; border-bottom: 2px solid #000000bb; padding-bottom: 10px; margin-bottom: 40px;">Jose
        Patiño - Riwi
        Developer</h1>
    <section
        style="border: solid  #333 0.5px; border-radius: 10px; margin: 2cm; box-shadow: 0 1px 4px; padding-left: 1cm; padding-bottom: 0.70cm; padding-right: 1cm;">
        <h2 style="text-align: center;border-bottom: 2px dashed #ccc">About Me</h2>
        <p>Hello, I am Jose.<br>
        I love creating attractive and funcional websites and am constantly learning to improve my skills.
        My dream is to become one of the best full sctack developer in the world, so i can create incredible things
        and contribute to technological world.</p>
    </section>
    <img src="/imagenes/empresario.jpg" alt="Jose's photo" width="200">
    <section>
        <h2>Skills</h2>
        <ul>
            <li>HTML & CSS</li>
            <li>Python, JavaScript</li>
            <li>Git, GitHub</li>
            <li>Team Work</li>
            <li>Effective Comunication</li>
            <li>Creativity and Adaptability</li>
        </ul>
    </section>

    <section>
        <h2>Projects</h2>
        <h3>Project 1: Portafolio Website</h3>
        <p>This is my first project where i built a personal portfolio using only HTML. </p>
    </section>
    <img src="https://empresa.org.ar/wp-content/uploads/2019/01/gestion-de-proyectos-1-820x535.jpeg"
        alt="project portfolio image" width="300">
    <table>
        <tr>
            <th>Project Name</th>
            <th>Technologies Used</th>
            <th>Link</th>
        </tr>
        <tr>
            <td>Portfolio Website</td>
            <td>HTML</td>
        </tr>
    </table>
    <form action="/send" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <input type="submit" value="send">
    </form>
    <h3>Social Media</h3>
    <a href="https://github.com/JosepoMP" target="_blank">GitHub</a>
    <a href="https://www.instagram.com/josemig.p/?next=%2Fp%2FDJekYInRmLm%2F" target="_blank">Instagram</a>

    <nav>
        <a href="#about-me">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</body>

</html>
