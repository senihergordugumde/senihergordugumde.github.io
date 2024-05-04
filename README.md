<div align="right">
    <button id="darkModeButton" onclick="toggleDarkMode()">🌗</button>
</div>

# Welcome to My Page  
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Apple_logo_black.svg/814px-Apple_logo_black.svg.png" alt="Apple Logo" class="animate-logo" width="100" height="100">

---

## About Me

Hello! I'm [Emir AKSU](), and here's a little about me.

---

### Projects

#### Baraj24
- Developed an iOS application that displays the current and historical daily water levels of dams in Turkey.
- Utilized MVC architecture and managed data with Firebase.
- Created the user interface using Programmatic UI methods.
- Integrated the Charts library to visualize the data with graphs and organized the information using Table View.
- Managed notifications using One Signal Notifications.

[![App Store](https://img.shields.io/badge/App%20Store-0D96F6?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com/us/app/barajlar%C4%B1n-doluluk-oranlar%C4%B1/id6466598170)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/senihergordugumde/baraj24-IOS)

---

#### Noteor
- Noteor is a comprehensive application that includes features like a To-Do list, calendar, notifications, voice-to-text input, and encryption.
- Developed under the MVC architecture using Firebase as the database.
- Combined Custom UI with Programmatic UI techniques to create a user-friendly interface.
- Integrated AVFoundation for voice-to-text input and used Table View and Collection View to organize content.
- Adopted a clean and modular coding approach and integrated encryption techniques to ensure data security.
- Consistently followed evolving iOS technologies to adhere to best practices.

[![App Store](https://img.shields.io/badge/App%20Store-0D96F6?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com/tr/app/noteor/id6499096266?l=tr)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/senihergordugumde/noteor)

---

### Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emir-aksu-118b5421b/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/senihergordugumde)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emiraksu1608@gmail.com)

<script>
function toggleDarkMode() {
    document.body.classList.toggle("dark-mode");
}

// Add dark-mode class to style
var style = document.createElement('style');
style.type = 'text/css';
style.innerHTML = `
    .dark-mode {
        background-color: #121212; 
        color: white; 
        transition: background-color 0.3s, color 0.3s;
    }

    .dark-mode img {
        filter: brightness(0.8);
        transition: filter 0.3s;
    }

    .dark-mode a {
        color: #BB86FC;
        transition: color 0.3s;
    }

    .dark-mode button {
        background-color: #BB86FC;
        color: #121212;
        border: none;
        padding: 0.5em;
        cursor: pointer;
        border-radius: 5px;
        transition: background-color 0.3s, color 0.3s;
    }

    .animate-logo {
        animation: bounce 2s infinite alternate;
    }

    @keyframes bounce {
        from {
            transform: translateY(0);
        }
        to {
            transform: translateY(-10px);
        }
    }
`;
document.head.appendChild(style);
</script>
