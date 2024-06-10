# URL Shortener

URL Shortener is a web application that allows users to shorten long URLs into compact, easily shareable links. This project demonstrates the use of modern web development technologies to create a functional and user-friendly URL shortening service.

## Table of Contents 📚

- [Introduction](#introduction)
- [Features](#features)
- [Screenshot](#screenshot)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction🚀

URL Shortener is a simple and efficient tool to convert long URLs into short, manageable links. The application provides a clean and responsive interface, allowing users to generate shortened URLs quickly and track their usage.

## Features🛠️

- **URL Shortening**: Convert long URLs into short, easy-to-share links.
- **Link Management**: View and manage your shortened URLs.
- **Analytics**: Track the number of clicks on your shortened links.
- **Responsive Design**: Accessible on various devices, including desktops and mobiles.
- **User Authentication**: Secure your links with user accounts (optional feature).

## Screenshot📷

![URL Shortener](https://github.com/BoddepallyVenkatesh06/URL-Shortener/blob/main/Screenshot/Screenshot_1.png)
![URL Shortener](https://github.com/BoddepallyVenkatesh06/URL-Shortener/blob/main/Screenshot/Screenshot_2.png)

## Technologies Used🖥️

- **Frontend**: React.js, Redux, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Deployment**: Docker, Heroku

## Getting Started🎯

### Prerequisites📋

Before you begin, ensure you have the following installed on your system:
- Node.js
- npm (Node Package Manager)
- MongoDB
- Docker (optional, for containerization)

### Installation⚙️

1. Clone the repository:

```bash
git clone https://github.com/BoddepallyVenkatesh06/URL-Shortener.git
cd url-shortener
```

2. Install frontend dependencies:

```bash
cd client
npm install
```

3. Install backend dependencies:

```bash
cd ../server
npm install
```

## Usage📈

### Running the Application

1. Start the MongoDB server (if not using Docker):

```bash
mongod
```

2. Start the backend server:

```bash
cd server
npm start
```

3. Start the frontend development

server:

```bash
cd ../client
npm start
```

### Building for Production

1. Build the frontend for production:

```bash
cd client
npm run build
```

2. Start the backend server in production mode:

```bash
cd ../server
NODE_ENV=production npm start
```

### Docker Deployment

1. Build and run the Docker containers:

```bash
docker-compose up --build
```

## Contributing❤️

Contributions are welcome! If you'd like to contribute to URL Shortener, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License📝

```
MIT License

© 2024 Venky Kumar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
