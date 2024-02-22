# Book-Search-Engine-GraphQL

This application allows users to search for books, save them to their account, and manage their saved books.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Deployment](#deployment)
- [License](#license)

## Introduction

The Book Search and Management App provides users with a platform to search for books using the Google Books API, save their favorite books to their account, and manage their saved book collection.

## Features

- Search for books by title, author, or keyword
- View detailed information about each book, including title, author(s), description, and cover image
- Save books to user accounts for future reference
- Remove books from saved collection
- User authentication and authorization

## Technologies

- **Frontend**: React.js, React Bootstrap, Apollo Client
- **Backend**: Node.js, Express.js, Apollo Server, MongoDB, Mongoose
- **Authentication**: JSON Web Tokens (JWT), bcrypt
- **GraphQL**: The backend of this application uses GraphQL for querying and mutating data. The Apollo Server handles GraphQL operations and communicates with the MongoDB database.
- **API**: Google Books API
- **Deployment**: Heroku

## Installation

1. Clone the repository: `git clone https://github.com/MahmoudAhmed0528/Book-Search-Engine-GraphQL`
2. Navigate to the project directory: `cd Book-Search-Engine-GraphQL`
3. Install dependencies for the frontend and backend:`npm install`
4. Set up environment variables:

- Create a `.env` file in the `server` directory and add
  `JWT_SECRET=your_secret-key`
  `JWT_EXPIRATION=your_expiration_key`

5. Start the frontend and backend server:
   `cd Book-Search-Engine-GraphQL`
   `npm run develop`

## Usage

1. Register for an account or log in if you already have one.
2. Use the search bar to look for books by title, author, or keyword.
3. Click on a book to view detailed information.
4. Click the "Save this Book!" button to add a book to your saved collection.
5. Go to the "Saved Books" page to view and manage your saved books.
6. To remove a book from your collection, click the "Delete this Book!" button.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes and commit them (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Create a new Pull Request

## Deployment

- **Heroku:** [Link to deployed App](#)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
