# Revenant Card - Dynamic Discord Profile Card

![Revenant Card](https://eliasdiscord.000webhostapp.com/)

**Revenant Card** is a dynamic user card created for Discord profiles. This repository contains the HTML and CSS code for building this card. It displays user information, including their profile picture, badges, status, and social media connections. Additionally, it fetches and displays the user's Discord status in real-time using the Lanyard API.

## Table of Contents

- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Features](#features)
- [Customization](#customization)
- [Real-Time Discord Status](#real-time-discord-status)
- [Credits](#credits)
- [License](#license)

## Getting Started

To use the Revenant Card on your Discord profile, follow these steps:

1. Clone the repository to your local machine using the following command:
   ```
   git clone <repository-url>
   ```

2. Open the `index.html` file in a web browser to view the Revenant Card.

## Project Structure

The project includes the following files and directories:

- `index.html`: The main HTML file that structures the Revenant Card.
- `assets/`: This directory contains subdirectories for CSS, JavaScript, images, badges, logos, and more.
- `assets/CSS/styles.css`: The CSS file responsible for styling the Revenant Card.
- `assets/JS/demo.js`: A JavaScript file used to fetch and update the user's Discord status.
- Various image files and badges used in the card.

## Features

The Revenant Card offers the following features:

- Display of user profile picture, badges, and status dot.
- Information about the user's roles, including custom role colors.
- Social media connections with icons.
- Real-time display of the user's Discord status using the Lanyard API.

## Customization

You can easily customize the Revenant Card to fit your preferences:

- Replace the profile picture, banner, and badge images in the `assets/` directory with your own.
- Update the user's information, including their name, username, and About Me section in the HTML file.
- Modify the roles and their colors in the HTML file to match your server's roles.
- Replace the social media connection links and icons with your own.

## Real-Time Discord Status

The card uses JavaScript to fetch the user's Discord status from the Lanyard API and updates the status dot accordingly. To set up real-time status updates for your own Discord user, replace the `discordUserId` variable with your Discord user ID in the JavaScript code.

```javascript
const discordUserId = 'YOUR_DISCORD_USER_ID';
```

## Credits

We would like to give credit to the following:

- The Font Awesome icon library for providing icons used in the card.
- The Lanyard API for powering the real-time Discord status updates.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to fork and modify this code to create your own customized user card for Discord profiles. Enjoy showcasing your profile with the Revenant Card!
