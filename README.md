<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emir AKSU - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="header-logo">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Apple_logo_black.svg/814px-Apple_logo_black.svg.png" alt="Apple Logo">
                <h1>Emir AKSU</h1>
            </div>
            <button id="darkModeButton" onclick="toggleDarkMode()">🌗</button>
        </div>
    </header>

    <main>
        <section id="about-me">
            <div class="container">
                <h2>About Me</h2>
                <p>Hello! I'm Emir AKSU, and here's a little about me.</p>
            </div>
        </section>

        <section id="projects">
            <div class="container">
                <h2>Projects</h2>

                <div class="project">
                    <h3>Baraj24</h3>
                    <ul>
                        <li>Developed an iOS application that displays the current and historical daily water levels of dams in Turkey.</li>
                        <li>Utilized MVC architecture and managed data with Firebase.</li>
                        <li>Created the user interface using Programmatic UI methods.</li>
                        <li>Integrated the Charts library to visualize the data with graphs and organized the information using Table View.</li>
                        <li>Managed notifications using One Signal Notifications.</li>
                    </ul>
                    <div class="links">
                        <a href="https://apps.apple.com/us/app/barajlar%C4%B1n-doluluk-oranlar%C4%B1/id6466598170" class="button">App Store</a>
                        <a href="https://github.com/senihergordugumde/baraj24-IOS" class="button">GitHub</a>
                    </div>
                </div>

                <div class="project">
                    <h3>Noteor</h3>
                    <ul>
                        <li>Noteor is a comprehensive application that includes features like a To-Do list, calendar, notifications, voice-to-text input, and encryption.</li>
                        <li>Developed under the MVC architecture using Firebase as the database.</li>
                        <li>Combined Custom UI with Programmatic UI techniques to create a user-friendly interface.</li>
                        <li>Integrated AVFoundation for voice-to-text input and used Table View and Collection View to organize content.</li>
                        <li>Adopted a clean and modular coding approach and integrated encryption techniques to ensure data security.</li>
                        <li>Consistently followed evolving iOS technologies to adhere to best practices.</li>
                    </ul>
                    <div class="links">
                        <a href="https://apps.apple.com/tr/app/noteor/id6499096266?l=tr" class="button">App Store</a>
                        <a href="https://github.com/senihergordugumde/noteor" class="button">GitHub</a>
                    </div>
                </div>
            </div>
        </section>

        <section id="contact">
            <div class="container">
                <h2>Contact</h2>
                <div class="contact-links">
                    <a href="https://www.linkedin.com/in/emir-aksu-118b5421b/" class="contact-button">LinkedIn</a>
                    <a href="https://github.com/senihergordugumde" class="contact-button">GitHub</a>
                    <a href="mailto:emiraksu1608@gmail.com" class="contact-button">Email</a>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>© 2024 Emir AKSU</p>
        </div>
    </footer>

    <script>
        function toggleDarkMode() {
            document.body.classList.toggle("dark-mode");
        }
    </script>
</body>
</html>
