# Petgram

**Petgram** is a social media platform tailored specifically for pet owners and pet lovers. Built using the MERN stack (MySQL, Express.js, React.js, and Node.js), it allows users to create personalized profiles for their pets, share updates, follow others, and foster a vibrant pet-loving community.

---

## Features

- **Pet Profiles** – Create dedicated profiles for pets, complete with bios, photos, and milestones
- **News Feed** – Post photos, videos, and updates to a dynamic community feed
- **Story Sharing** – Document and share stories or moments from your pet’s life
- **Social Interactions** – Like, comment, follow/unfollow pet profiles
- **Dark Mode** – Switch between light and dark themes
- **Real-time Updates** – Content and interactions update without needing to reload
- **Pet Care Resources** – Access curated articles and advice on pet grooming, health, and training

---

## Tech Stack

- **Frontend**: React.js, HTML5, CSS3, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Authentication**: JSON Web Tokens (JWT)
- **Version Control**: Git & GitHub

---

## Project Structure (Simplified)

```
Petgram/
├── client/               # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       └── App.js
├── server/               # Node/Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── .env
├── package.json
├── README.md
└── LICENSE
```

---

## How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/ShashaankBhat/Petgram.git
   cd Petgram
   ```

2. **Install frontend and backend dependencies**
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. **Configure environment variables**
   Create a `.env` file in the server directory with your database and JWT config.

4. **Run both servers**
   ```bash
   cd server
   node server.js

   # In another terminal
   cd client
   npm start
   ```

---

## Future Enhancements

- Native mobile apps (Android & iOS)
- AI-powered pet content recommendations
- Marketplace for pet products
- Pet adoption and rescue integration
- Community groups and forums

---

## Author

**Shashank Bhat**  
Final-year Computer Science Engineering student at MGM University  
[LinkedIn](https://www.linkedin.com/in/shashaankbhat) • [GitHub](https://github.com/ShashaankBhat)

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.