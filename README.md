# 🍴 GrabitGo Food Delivery Web App

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/username/GrabitGo-Food-Delivery-Web-App/blob/main/LICENSE)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D16.0.0-brightgreen)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-%3E%3D5.0-green)](https://www.mongodb.com/)

A full-stack food delivery platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js). GrabitGo provides a seamless ordering experience for customers and powerful management tools for restaurant administrators.

## 📸 Screenshots

### Customer Interface
![Home Page](https://github.com/shubheshkumar0/GrabitGo-Food-Delivery-Web-App/blob/main/Screenshot%202026-01-21%20165743.png?raw=true)
*Beautiful landing page with hero section and call-to-action*

![Menu Categories](https://github.com/shubheshkumar0/GrabitGo-Food-Delivery-Web-App/blob/main/Screenshot%202026-01-21%20165805.png?raw=true)
*Explore diverse menu categories and discover top dishes near you*

### Admin Dashboard
![Order Management](https://github.com/shubheshkumar0/GrabitGo-Food-Delivery-Web-App/blob/main/Screenshot%202026-01-21%20165819.png?raw=true)
*Real-time order tracking and management dashboard*

## ✨ Features

- **🔐 Secure Authentication** - Password hashing and salting for both customers and administrators
- **👨‍💼 Admin Dashboard** - Complete restaurant, menu, and order management system
- **📱 Responsive Design** - Optimized experience across desktop, tablet, and mobile devices
- **🚀 Real-time Updates** - Live order tracking and status notifications
- **🎨 Intuitive Interface** - User-friendly design for effortless navigation and ordering
- **⚡ High Performance** - Scalable architecture built on the MERN stack

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [MongoDB](https://www.mongodb.com/) (v5 or higher)
- npm or yarn package manager
- Git

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/username/GrabitGo-Food-Delivery-Web-App.git
   cd GrabitGo-Food-Delivery-Web-App
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure environment variables**
   
   Create a `.env` file in the root directory:
   ```env
   MONGO_URI=your_mongodb_connection_string
   NODE_ENV=development
   PORT=5000
   JWT_SECRET=your_jwt_secret_key
   ```

4. **Start the application**
   ```bash
   npm start
   # or
   yarn start
   ```

5. **Access the application**
   
   Open your browser and navigate to `http://localhost:5000`

## 📁 Project Structure

```
GrabitGo-Food-Delivery-Web-App/
├── client/                 # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── services/
│       └── App.js
├── server/                 # Express backend
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── .env.example
├── package.json
└── README.md
```

## 🔧 Configuration

### Environment Variables

| Variable | Description | Example |
|----------|-------------|---------|
| `MONGO_URI` | MongoDB connection string | `mongodb://localhost:27017/grabitgo` |
| `NODE_ENV` | Application environment | `development` or `production` |
| `PORT` | Server port number | `5000` |
| `JWT_SECRET` | Secret key for JWT tokens | `your_secret_key_here` |

## 💻 Usage

### Starting the Development Server

```bash
# Start both client and server
npm run dev

# Start server only
npm run server

# Start client only
npm run client
```

### Building for Production

```bash
npm run build
```

## 🛠️ Tech Stack

**Frontend:**
- React.js
- React Router
- Axios
- CSS3 / Styled Components

**Backend:**
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt

## 🤝 Contributing

We welcome contributions to GrabitGo! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

Please ensure your code follows the project's coding standards and includes appropriate tests.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **Your Name** - *Initial work* - [YourGitHub](https://github.com/username)

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape GrabitGo
- Inspired by modern food delivery platforms
- Built with the amazing MERN stack community tools

## 📞 Support

If you have any questions or need help, please:
- Open an issue on GitHub
- Contact us at support@grabitgo.com
- Check out our [Documentation](https://github.com/username/GrabitGo-Food-Delivery-Web-App/wiki)

---

**Made with ❤️ by the GrabitGo Team**
