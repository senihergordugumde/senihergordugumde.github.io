# Welcome to My Page   <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Apple_logo_black.svg/814px-Apple_logo_black.svg.png" alt="Apple Logo" width="100" height="100">

<div align="center">
    <button id="darkModeButton" onclick="toggleDarkMode()">🌗</button>
</div>

## About Me
Hello! I'm [Emir AKSU](), and here's a little about me.

### Projects
- **Baraj24:**  Developed an iOS application that displays the current and historical daily water levels of dams in Turkey. In this project, I used the MVC architecture and managed data with Firebase. I created the user interface using Programmatic UI methods. Additionally, I integrated the Charts library to visualize the data with graphs and organized the information using Table View. For managing notifications, I used One Signal Notifications.
   [AppStore](https://apps.apple.com/us/app/barajlar%C4%B1n-doluluk-oranlar%C4%B1/id6466598170) |
   [Github](https://github.com/senihergordugumde/baraj24-IOS)

  
- **Noteor:** Noteor is a comprehensive application that includes features like a To-Do list, calendar, notifications, voice-to-text input, and encryption. Developed under the MVC architecture, I used Firebase as the database for this project and combined Custom UI with Programmatic UI techniques to create a user-friendly interface. I integrated AVFoundation to enable voice-to-text input for users and used Table View and Collection View to organize content. During development, I adopted a clean and modular coding approach and integrated encryption techniques to ensure the security of user data. I consistently followed the evolving iOS technologies to ensure the project adhered to best practices.
[AppStore](https://apps.apple.com/tr/app/noteor/id6499096266?l=tr) |
[Github](https://github.com/senihergordugumde/noteor)

### Contact
- **LinkedIn:** [My LinkedIn](https://www.linkedin.com/in/emir-aksu-118b5421b/)
- **GitHub:** [My GitHub](https://github.com/senihergordugumde)
- **Email:** emiraksu1608@gmail.com

<script>
function toggleDarkMode() {
    var element = document.body;
    element.classList.toggle("dark-mode");
}

// Add dark-mode class to style
var style = document.createElement('style');
style.type = 'text/css';
style.innerHTML = '.dark-mode { background-color: #121212; color: white; }';
document.getElementsByTagName('head')[0].appendChild(style);
</script>
