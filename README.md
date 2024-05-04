<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Emir AKSU's professional portfolio showcasing iOS development projects, including Baraj24 and Noteor.">
    <meta name="keywords" content="Emir AKSU, iOS Developer, Baraj24, Noteor, portfolio, projects">
    <meta name="author" content="Emir AKSU">
    <title>Emir AKSU - iOS Developer</title>
    <link rel="icon" href="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Apple_logo_black.svg/814px-Apple_logo_black.svg.png" type="image/png">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            transition: background-color 0.5s ease, color 0.5s ease;
        }

        .dark-mode {
            background-color: #121212;
            color: white;
        }

        .dark-mode img {
            filter: brightness(0.8);
        }   

        a{
            color : #F9546C;
        }
        .dark-mode a {
            color: #F9546C;
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

        .carousel img {
            width: 100%; /* Full width of the carousel */
            height: 400px; /* Fixed height for all images */
            object-fit:contain; /* Cover the container without distorting the aspect ratio */
            object-position: center; /* Center the image within the container */
        }
        
        .btn-social {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            margin-right: 8px;
            padding: 0.5em 1em;
            border-radius: 5px;
            color: #ffffff;
        }

        .btn-linkedin {
            background-color: #0077B5;
        }

        .btn-github {
            background-color: #333;
        }

        .btn-email {
            background-color: #D44638;
        }

        .project-list-item {
            padding: 10px 0;
        }

        .carousel-item .row {
            display: flex;
            justify-content: center;
            gap: 10px;
        }

        .carousel-item img {
            max-width: 48%;
            object-fit:contain;
          
        }

        .carousel-control-prev-icon,
        .carousel-control-next-icon {
            background-color: #F9546C; /* Change the color here */
            border-radius: 50%;
            padding: 10px;
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

        <h1 class="text-center my-4">Emir AKSU</h1>
        <h2 class="text-center mb-4">iOS Developer</h2>

        <hr>

        <section id="about-me">
            <h2 class="mt-5">About Me</h2>
            <p>Hello! I'm <a href="#">Emir AKSU</a>, an iOS developer with a passion for creating intuitive and impactful mobile applications.</p>
        </section>

        <section id="projects">
            <h2 class="mt-5">Projects</h2>

            <article class="mt-4">
                <h3>Baraj24</h3>
                <ul>
                    <li class="project-list-item">Developed an iOS application that displays the current and historical daily water levels of dams in Turkey.</li>
                    <li class="project-list-item">Utilized MVC architecture and managed data with Firebase.</li>
                    <li class="project-list-item">Created the user interface using Programmatic UI methods.</li>
                    <li class="project-list-item">Integrated the Charts library to visualize the data with graphs and organized the information using Table View.</li>
                    <li class="project-list-item">Managed notifications using One Signal Notifications.</li>
                </ul>

                <div id="baraj24Carousel" class="carousel slide mb-3" data-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <div class="row">
                                <img src="/Volumes/CrucialX6/Downloads/pickCity.png" class="d-block" alt="Baraj24 Screenshot 1">
                                <img src="https://github.com/senihergordugumde/senihergordugumde/blob/main/ASSETS/baraj24/map.png?raw=true" class="d-block" alt="Baraj24 Screenshot 2">
                            </div>
                        </div>
                        <!-- Add more carousel items here as needed -->
                    </div>
                    <a class="carousel-control-prev" href="#baraj24Carousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#baraj24Carousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>

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
                    <li class="project-list-item">Noteor is a comprehensive application that includes features like a To-Do list, calendar, notifications, voice-to-text input, and encryption.</li>
                    <li class="project-list-item">Developed under the MVC architecture using Firebase as the database.</li>
                    <li class="project-list-item">Combined Custom UI with Programmatic UI techniques to create a user-friendly interface.</li>
                    <li class="project-list-item">Integrated AVFoundation for voice-to-text input and used Table View and Collection View to organize content.</li>
                    <li class="project-list-item">Adopted a clean and modular coding approach and integrated encryption techniques to ensure data security.</li>
                    <li class="project-list-item">Consistently followed evolving iOS technologies to adhere to best practices.</li>
                </ul>

                <div id="noteorCarousel" class="carousel slide mb-3" data-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <div class="row">
                                <img src="https://github.com/senihergordugumde/senihergordugumde.github.io/blob/main/images/noteor/login.png?raw=true" class="d-block" alt="Noteor Screenshot 1">
                                <img src="https://github.com/senihergordugumde/senihergordugumde.github.io/blob/main/images/noteor/home.png?raw=true" class="d-block" alt="Noteor Screenshot 2">
                            </div>
                        </div>
                        <div class="carousel-item">
                            <div class="row">
                                <img src="https://github.com/senihergordugumde/senihergordugumde.github.io/blob/main/images/noteor/addTask.png?raw=true" class="d-block" alt="Noteor Screenshot 3">
                                <img src="https://github.com/senihergordugumde/senihergordugumde.github.io/blob/main/images/noteor/notes.png?raw=true" class="d-block" alt="Noteor Screenshot 4">
                            </div>
                        </div>
                        <div class="carousel-item">
                            <div class="row">
                                <img src="https://github.com/senihergordugumde/senihergordugumde.github.io/blob/main/images/noteor/profile.png?raw=true" class="d-block" alt="Noteor Screenshot 5">
                                <img src="https://github.com/senihergordugumde/senihergordugumde.github.io/blob/main/images/noteor/calendar.png?raw=true" class="d-block" alt="Noteor Screenshot 6">
                            </div>
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#noteorCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#noteorCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>

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
                <a href="https://www.linkedin.com/in/emir-aksu-118b5421b/" class="btn btn-social btn-linkedin mr-2" target="_blank">
                    <i class="fab fa-linkedin"></i> LinkedIn
                </a>
                <a href="https://github.com/senihergordugumde" class="btn btn-social btn-github mr-2" target="_blank">
                    <i class="fab fa-github"></i> GitHub
                </a>
                <a href="mailto:emiraksu1608@gmail.com" class="btn btn-social btn-email" target="_blank">
                    <i class="fas fa-envelope"></i> Email
                </a>
            </div>
        </section>
    </div>
</div>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/js/all.min.js"></script>
<script>
    function toggleDarkMode() {
        document.body.classList.toggle("dark-mode");
    }
</script>

</body>
</html>
