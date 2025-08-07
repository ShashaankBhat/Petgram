# Petgram

**Petgram** is a social media platform tailored specifically for pet owners and pet lovers. Built using the MERN stack (MongoDB, Express.js, React.js, and Node.js), it allows users to create personalized profiles for their pets, share updates, follow others, and foster a vibrant pet-loving community.

---

## Features

-   **Pet Profiles** – Create dedicated profiles for pets, complete with bios, photos, and milestones
-   **News Feed** – Post photos, videos, and updates to a dynamic community feed
-   **Story Sharing** – Document and share stories or moments from your pet’s life
-   **Social Interactions** – Like, comment, follow/unfollow pet profiles
-   **Dark Mode** – Switch between light and dark themes
-   **Real-time Updates** – Content and interactions update without needing to reload
-   **Pet Care Resources** – Access curated articles and advice on pet grooming, health, and training

---

## Tech Stack

-   **Frontend**: React.js, HTML5, CSS3, JavaScript
-   **Backend**: Node.js, Express.js
-   **Database**: MongoDB
-   **Authentication**: JSON Web Tokens (JWT)
-   **Version Control**: Git & GitHub

---

## 📸 Screenshots

---

### 1. Registration Page
* Users can create a new account to join the platform.
    ![A user signing up on the Petgram registration page]<img width="1919" height="1018" alt="Screenshot 2025-08-07 125812" src="https://github.com/user-attachments/assets/43168c5f-78b9-4414-8b45-8e0477d20b2c" />


---

### 2. Login Page
* Secure login for existing users.
    ![A user logging into the Petgram application](https://github.com/user-attachments/assets/b3310f84-b043-4ce4-8e10-94e8a1d7c470)

---

### 3. Home Feed
* The main dashboard where users can see posts from others. Includes a "Who to follow" suggestion sidebar.
    ![The main home feed of Petgram showing posts from other users](https://github.com/user-attachments/assets/ba0800b9-1383-4a16-832f-45b637508006)

---

### 4. User Profile Page
* Dedicated pages for each pet's profile, showing their posts and follower counts.
    ![A profile page for a pet named Tommy The Dog](https://github.com/user-attachments/assets/3dd035b8-53e7-4959-b1d3-3532c2534a41)

---

### 5. Creating a Post
* Users can easily create new posts with text and images.
    ![The user interface for creating a new post with an image of a shih tzu](https://github.com/user-attachments/assets/2b528b9a-4cce-47a3-b0ac-63d1a4918f6c)

---

### 6. Viewing Comments
* An interactive comment section for each post.
    ![The comments section expanded on a post in Petgram](https://github.com/user-attachments/assets/b05b38ed-3574-4b52-b8d9-e380f68e0d47)

---

### 7. Notifications Page
* A dedicated page to view notifications and interactions.
    ![The notifications page in Petgram, currently showing no new notifications](https://github.com/user-attachments/assets/bcf1cc11-8f9f-4404-b9c1-54c34a2c5a05)

---

## How to Run Locally

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/ShashaankBhat/Petgram.git](https://github.com/ShashaankBhat/Petgram.git)
    cd Petgram
    ```

2.  **Install frontend and backend dependencies**
    ```bash
    cd frontend
    npm install
    cd ../backend
    npm install
    ```

3.  **Configure environment variables**
    Create a `.env` file in the `backend` directory with your database and JWT config.

4.  **Run both servers**
    ```bash
    # In one terminal
    cd backend
    npm run dev

    # In another terminal
    cd frontend
    npm run dev
    ```

---

## Future Enhancements

-   Native mobile apps (Android & iOS)
-   AI-powered pet content recommendations
-   Marketplace for pet products
-   Pet adoption and rescue integration
-   Community groups and forums

---

## Author

**Shashank Bhat** Final-year Computer Science Engineering student at MGM University  
[LinkedIn](https://www.linkedin.com/in/shashankbhat2004) • [GitHub](https://github.com/ShashaankBhat)

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
