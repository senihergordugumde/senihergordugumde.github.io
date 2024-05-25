<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emir AKSU's Page</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            transition: background-color 0.5s ease, color 0.5s ease;
        }

        .dark-mode {
            background-color: #121212;
            color: white;
        }

        .dark-mode img {
            filter: brightness(0.8);
        }

        .dark-mode a {
            color: #BB86FC;
        }

        .dark-mode button {
            background-color: #BB86FC;
            color: #121212;
            border: none;
            padding: 0.5em;
            cursor: pointer;
            border-radius: 5px;
        }

        #darkModeButton {
            position: fixed;
            top: 10px;
            right: 10px;
            background-color: #f8f9fa;
            color: #343a40;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.5s ease, color 0.5s ease;
        }

        .dark-mode #darkModeButton {
            background-color: #BB86FC;
            color: white;
        }

        .content {
            max-width: 800px;
            margin: 50px auto;
        }
    </style>
</head>
<body>

<div class="container">
    <button id="darkModeButton" onclick="toggleDarkMode()">🌗</button>

    <div class="content">
        <div class="text-center">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Apple_logo_black.svg/814px-Apple_logo_black.svg.png" alt="Apple Logo" width="100" height="100">
        </div>

        <h1 class="text-center my-4">Welcome to My Page</h1>

        <hr>

        <section id="about-me">
            <h2 class="mt-5">About Me</h2>
            <p>Hello! I'm <a href="#">Emir AKSU</a>, and here's a little about me.</p>
        </section>

        <section id="projects">
            <h2 class="mt-5">Projects</h2>

            <article class="mt-4">
                <h3>Baraj24</h3>
                <ul>
                    <li>Developed an iOS application that displays the current and historical daily water levels of dams in Turkey.</li>
                    <li>Utilized MVC architecture and managed data with Firebase.</li>
                    <li>Created the user interface using Programmatic UI methods.</li>
                    <li>Integrated the Charts library to visualize the data with graphs and organized the information using Table View.</li>
                    <li>Managed notifications using One Signal Notifications.</li>
                </ul>
                <div class="d-flex align-items-center">
                    <a href="https://apps.apple.com/us/app/barajlar%C4%B1n-doluluk-oranlar%C4%B1/id6466598170" class="btn btn-primary mr-2" target="_blank">
                        App Store
                    </a>
                    <a href="https://github.com/senihergordugumde/baraj24-IOS" class="btn btn-dark" target="_blank">
                        GitHub
                    </a>
                </div>
            </article>

            <article class="mt-4">
                <h3>Noteor</h3>
                <ul>
                    <li>Noteor is a comprehensive application that includes features like a To-Do list, calendar, notifications, voice-to-text input, and encryption.</li>
                    <li>Developed under the MVC architecture using Firebase as the database.</li>
                    <li>Combined Custom UI with Programmatic UI techniques to create a user-friendly interface.</li>
                    <li>Integrated AVFoundation for voice-to-text input and used Table View and Collection View to organize content.</li>
                    <li>Adopted a clean and modular coding approach and integrated encryption techniques to ensure data security.</li>
                    <li>Consistently followed evolving iOS technologies to adhere to best practices.</li>
                </ul>
                <div class="d-flex align-items-center">
                    <a href="https://apps.apple.com/tr/app/noteor/id6499096266?l=tr" class="btn btn-primary mr-2" target="_blank">
                        App Store
                    </a>
                    <a href="https://github.com/senihergordugumde/noteor" class="btn btn-dark" target="_blank">
                        GitHub
                    </a>
                </div>
            </article>
        </section>

        <section id="contact" class="mt-5">
            <h2>Contact</h2>
            <div class="d-flex align-items-center">
                <a href="https://www.linkedin.com/in/emir-aksu-118b5421b/" class="btn btn-info mr-2" target="_blank">
                    LinkedIn
                </a>
                <a href="https://github.com/senihergordugumde" class="btn btn-dark mr-2" target="_blank">
                    GitHub
                </a>
                <a href="mailto:emiraksu1608@gmail.com" class="btn btn-danger" target="_blank">
                    Email
                </a>
            </div>
        </section>
    </div>
</div>

<script>
    function toggleDarkMode() {
        document.body.classList.toggle("dark-mode");
    }
</script>

</body>
</html>
