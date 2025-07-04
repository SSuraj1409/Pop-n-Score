<h1 align="center">🎮 Pop 'n' Score – JavaScript Circle Popping Game</h1>

---

## 📝 Description

The name of my game is called **Pop 'n' Score**. It is an interactive online game that tests players’ reflexes and accuracy. The goal of the game is to click on circles that appear at random within a set amount of time, earning points for each successful click. The game also incorporates features such as **power-ups** to improve gameplay. The website for the game is built with **HTML, CSS, and JavaScript**, and includes features like **user registration**, **login**, and a **ranking system** that shows the **top 5 players**.


---

## 🔧 Technologies Used

- **Front-end**: HTML, CSS, JavaScript (Vanilla JS)
- **No frameworks or libraries used**
- **Responsive UI and event-driven logic**

---

## 🎮 How to Play

To play the game the user must be logged in first to access the game. If a user clicks the 'Play Now' button on the home page without being logged in they will be redirected to the login page instead of the game. Once logged in, players can start the game by clicking the 'Start Game' button which initiates a 2-minute timer. During this time colourful circles appear randomly on the screen in various sizes. For Each circle clicked earn points based on its size.

### 🟠 Scoring System:

- **40px circles** – 15 points  
- **50px circles** – 10 points  
- **60px circles** – 5 points

### ⚡ Power-Ups:

- **x2 Score Multiplier** – Doubles the player's current score when clicked.  
- **Freeze** – Freezes the timer for **5 seconds**, allowing players to continue scoring without time decreasing.

---

## 🖼️ Visual Overview of the Game

<h3>Home page:</h3>  
<div align="center">
<img src="https://i.imgur.com/4urfveR.png" width="80%" alt="Home"/>
</div>

<br/>

<h3>Sign up and Login page:</h3>  
The user sign-up page allows new players to register by entering their email, username, and password. The application performs validation to ensure the email is properly formatted, the username is not empty and does not exceed 12 characters, and the password is at least six characters long and includes both letters and numbers. If any of these checks fail, users receive clear error messages. Once the form is successfully submitted, they are redirected to the login page.
<br></br>
After registration, users can log in with their credentials. The system verifies the username and password against existing records and either grants access to the game or displays an error message for incorrect details. Upon successful login, the user's username appears in the navigation bar. Clicking on it reveals a dropdown menu with their highest score and a logout option, providing a personalized and interactive user experience.
<br></br>
<div align="center">
<img src="https://i.imgur.com/UrU5Io3.png" width="80%" alt="Sign up page"/>
<img src="https://i.imgur.com/GnXUlKD.png" width="80%" alt="Login page"/>
</div>

<br/>

<h3>Game page:</h3>  

<div align="center">
<img src="https://i.imgur.com/rZP0IS3.png" width="80%" alt="Home page after logging in"/>
</div>

<br/>

<h3>Forum Page:</h3>  
The Forum Page is the core of StudySpace, featuring six distinct subject categories. When a user clicks on a subject, they are redirected to its dedicated chat forum where they can:

- **Post questions or answer other users' questions.**

- **Upload files or images** to provide additional context or explanations for their posts.  
  A **"Remove File"** button allows users to delete any file mistakenly selected.

- **Use the Search Bar** to filter through discussions.  
  The search feature dynamically matches the user’s query with existing posts, displaying relevant results.  
  If no match is found, a message is shown saying **“No discussion found.”**

- **Sort discussions using the Sort Button:**  
  → When the button says **“Sort by Latest”**, clicking it will arrange posts from newest to oldest.  
  → When it says **“Sort by Oldest”**, clicking will organize discussions from oldest to newest.
<br></br>
<div align="center">
<img src="https://i.imgur.com/lwZTiP8.png" width="80%" alt="Forum page"/>
<img src="https://i.imgur.com/39h62Io.png" width="80%" alt="Forum Page"/>
<img src="https://i.imgur.com/T79wIiK.png" width="80%" alt="Forum page"/>
<img src="https://i.imgur.com/MTTLer7.png" width="80%" alt="Forum page"/>
<img src="https://i.imgur.com/yoE7XyT.png" width="80%" alt="Question input box in forum page"/>
</div>

<br/>


---

## 🔐 Login Requirement (Optional)

When integrated into a larger platform:
- Only logged-in users can play the game.
- Leaderboard data is restricted to authenticated users.
- Game progress and high scores can be tracked per user.

---

## 🗂️ File Structure

- `index.html` – Game structure  
- `style.css` – Game styling and layout  
- `game.js` – Game logic, timer, and interactions

---

## **🔒 Full source code available in a private repository. Please contact me for access.**
