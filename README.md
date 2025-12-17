<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="styles.css">
        <link rel="shortcut icon" href="images/icon.png">
        <title>Contact Me</title>willy rangel 
        <script src="contact.js" defer></script>
    </head>
    <body>
        <header>
            <div class="logo">
                <img src="images/icon.png">
            </div>
            <!-- use anchor tag for links -->
             <h1>My Portfolio</h1>
            <ul class="nav-bar"> <!--unordered list tag -->
                <li><a href="index.html">About Me</a></li> <!-- list item tag -->
                <li><a href="projects.html">Projects</a></li>
                <li><a href="experience.html">Experience</a></li>
                <li><a class="current" href="contact.html">Contact</a></li>
            </ul>
            <div class="socials">
                <a href="https://github.com/divyabajaj0025" target="_blank"><img src="images/github-logo.png"></a>
                <a href=""><img src="images/linkedin-logo.png"></a>
            </div>
        </header>

        <div class="content">
            <form name="contactMe" onsubmit="return validateForm();">
                <fieldset>
                    <legend>Contact Me</legend>
                    <label>Name:</label>
                    <input name="name" type="text"><br/>

                    <label>Email:</label>
                    <input name="email" type="email"><br/>

                    <label>Phone:</label>
                    <input name="phone" type="tel"><br/>

                    <label>Message:</label>
                    <textarea name="msg" rows="4" cols="50"></textarea><br/>

                    <label></label>
                    <input type="submit" value="Send Message!">
                </fieldset>
            </form>
        </div>

        <footer>
            Copyright &copy; CSCI 1101
        </footer>
    </body>
</html>
