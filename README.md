# MVC-tech-blog

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Links](#links)
- [Technologies](#technologies)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Description

Tech Blog is a social media based application that can be used to write about tech and all of its aspects. After signing up and loging in, users are able to post their own blog posts in their account dashboard. Users can also comment on others posts that are found on the main feed in the homepage.

## Installation

1. Clone the repository from GitHub.
2. Run `npm i` To install the neccesary dependencies.
3. Create a `.env` file to store your password credentials.
4. Run `mysql -u root -p` and proceed to enter your mysql password.
5. Run `source db/schema.sql` to create the database.
6. Exit the mysql shell by entering `quit`
7. Run `npm run seed` to seed your database from the root directory in the command line.
8. Run `npm start` from the command line to connect to the server.

## Usage

After the application is connected to the server, You will be able to view the main page with some of the posts on the feed. To create, comment, and edit posts, one must first login. Once the login button is clicked, one is directed to the signup and login page. If you have an existing account, a user can just login with their email and password credentials, but if not, they can utilize the signup form to create an account. Once logged in, a user is directed to their dashboard where they can create and edit their posts.

Login and Sign Up Page:
<img width="1440" alt="Screen Shot 2022-06-08 at 2 21 45 PM" src="https://user-images.githubusercontent.com/95589049/172693617-b8041573-1b44-4522-9743-157814532955.png">

Main Page:
<img width="1430" alt="Screen Shot 2022-06-08 at 2 21 37 PM" src="https://user-images.githubusercontent.com/95589049/172693704-1afc0e5b-1a80-4cdb-a1fe-aacd595dde7f.png">

User Dashboard:
<img width="1431" alt="Screen Shot 2022-06-08 at 2 21 26 PM" src="https://user-images.githubusercontent.com/95589049/172693767-0e4267ab-7995-4d9d-abda-5f37066c3afd.png">

## Links

Deployed application:

## Technologies

- JavaScript
- HTML
- CSS
- MySQL
- Sequelize
- Express

## License

This project is licensed under MIT license.

## Contributing

You can further contribute to the project by forking the repo and creating features to like and dislike posts.

## Questions

Reach me by email: asingh0328@yahoo.com

Github username: AjaypalGhuman

Github Profile Link: https://github.com/AjaypalGhuman
