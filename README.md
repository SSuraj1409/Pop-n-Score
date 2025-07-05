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
- **Time Extension** – Increases the game time by 5 seconds, giving players extra time to accumulate points.
  
<div align="center">
<img src="https://i.imgur.com/6YRjLOq.png" width="80%" alt="Home page after logging in"/>
</div>


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

<h3>About page:</h3>  

<div align="center">
<img src="https://i.imgur.com/RwzzG1O.png" width="80%" alt="Home page after logging in"/>
</div>

<br/>

<h3>Game page:</h3>  

<div align="center">
<img src="https://i.imgur.com/rZP0IS3.png" width="80%" alt="Home page after logging in"/>
</div>

<br/>

<h3>Leaderboard Page:</h3>  
The leaderboard tracks and displays players' highest scores. It only shows this data to users who are logged in, ensuring that only registered players can participate in the ranking system. If a player is not logged in, they will not have access to the information in the leaderboard.
<br></br>
When a logged-in player finishes a game, their highest score is recorded and compared against existing scores on the leaderboard. If their score is higher than previous entries, it updates their ranking. Conversely, if a player has a score of zero, they are not added to the leaderboard. The leaderboard showcases only the top 5 players, displaying their usernames and scores.
<br></br>
When users click on their username, a dropdown menu appears displaying their highest score and a logout button. Once the game is over, if the user achieves a new highest score, it will also be reflected in the navbar dropdown when clicking on the logged-in username. However, to see the updated highest score in the navbar, users need to reload the page.
<br></br>
<div align="center">
<img src="https://i.imgur.com/ucmsW1p.png" width="80%" alt="Forum page"/>
</div>

<br/>


---

## **🔒 Full source code available in a private repository. Please contact me for access.**
