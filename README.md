<div>
  <h1>Dot-Box</h1>
</div>

![Dot-1](https://github.com/GameSphere-MultiPlayer/Dot-Box/assets/133582566/c8b9bbbb-9230-4267-807b-b8e851f919ab)

<hr>

# About Our Project 💻
<div align="center">
<img src="https://forthebadge.com/images/badges/built-with-love.svg" />
<img src="https://forthebadge.com/images/badges/uses-brains.svg" />
<img src="https://forthebadge.com/images/badges/powered-by-responsibility.svg" />
  <br>
<img src="https://img.shields.io/github/repo-size/GameSphere-MultiPlayer/Dot-Box?style=for-the-badge" />
   <img src="https://img.shields.io/github/issues-pr/GameSphere-MultiPlayer/Dot-Box?style=for-the-badge" />

  <img src="https://img.shields.io/github/issues/GameSphere-MultiPlayer/Dot-Box?style=for-the-badge" />
  <img src="https://img.shields.io/github/issues-closed-raw/GameSphere-MultiPlayer/Dot-Box?style=for-the-badge" />
   <img src="https://img.shields.io/github/issues-pr-closed-raw/GameSphere-MultiPlayer/Dot-Box?style=for-the-badge" />
  <img src="https://img.shields.io/github/license/GameSphere-MultiPlayer/Dot-Box?style=for-the-badge" />
  <img src="https://img.shields.io/github/forks/GameSphere-MultiPlayer/Dot-Box?style=for-the-badge" />
  <img src="https://img.shields.io/github/stars/GameSphere-MultiPlayer/Dot-Box?style=for-the-badge" />
  <img src="https://img.shields.io/github/contributors/GameSphere-MultiPlayer/Dot-Box?style=for-the-badge" />
  <img src="https://img.shields.io/github/last-commit/GameSphere-MultiPlayer/Dot-Box?style=for-the-badge" />
  </div>

<hr>

  ## 🎮 Gaming Rule

The game is very simple and easy to play, it's a multiplayer game where each player gets one chance to play alternatively. The goal is to maximize the number of boxes owned. The game continues until no box is left unoccupied. 

### How to Play
1. **Setup:** At the start of the game, choose the number of squares you want to have by specifying the number of rows and columns. The range is from 5 to 30 for both rows and columns. Also, specify the number of players, which can be from 2 to 6.

2. **Gameplay:** 
   - Players take turns marking one side of a square on the board.
   - If a side completes a square along with previous marks, the player gets the box and an extra chance to play.
   - The game requires strategic thinking to maximize the number of boxes owned.

3. **Winning:** The player with the most boxes owned at the end of the game wins.

<hr>

## Dot Box Game Strategies

### 1. **Claiming Territory** 🏰
   - **Early Game:** Focus on securing territory to build a strong foundation. 
   - **Mid to Late Game:** Prioritize closing boxes to prevent opponents from claiming territory.

### 2. **Box Closure** 📦
   - **Immediate Closure:** Always close a box if possible, unless it would immediately grant your opponent an advantage.
   - **Forcing Closure:** Try to force your opponent into closing a box that would benefit you more than them.

### 3. **Defensive Play** 🛡️
   - **Blocking Moves:** Use blocking moves to prevent your opponent from closing boxes or claiming territory.
   - **Strategic Sacrifice:** Sacrifice a box to prevent your opponent from getting a bigger advantage.

### 4. **Offensive Play** ⚔️
   - **Box Stealing:** Aim to steal boxes from your opponent by closing boxes that they are about to complete.
   - **Forcing Mistakes:** Force your opponent into making mistakes by creating complex board states.

### 5. **Control the Center** 🎯
   - **Strategic Importance:** The center of the board is crucial for controlling the game. Try to maintain a strong presence there.
   - **Access Points:** Keep control of the access points to the center to limit your opponent's options.

### 6. **Predictive Play** 🔮
   - **Anticipating Moves:** Try to anticipate your opponent's moves and plan your strategy accordingly.
   - **Stay Flexible:** Be prepared to adapt your strategy based on your opponent's actions.

### 7. **Endgame Strategies** 🏁
   - **Counting Boxes:** Keep track of the number of boxes each player has closed to determine the best moves in the endgame.
   - **Protecting Lead:** If you're ahead, focus on protecting your lead rather than taking risks.

### 8. **Mind Games** 🧠
   - **Bluffing:** Occasionally make moves that seem advantageous to your opponent but actually benefit you in the long run.
   - **Psychological Warfare:** Use your opponent's expectations against them to gain an advantage.

<hr>

## Features :

- Multiplayer game supporting 2 to 6 players.
- Strategic gameplay requiring tactical thinking.
- Customizable board size with rows and columns from 5 to 30.
- Dynamic gameplay where players earn extra chances for completing squares.

<hr>

  # How to Contribute in our Project ? 🟢

If you are interested to contribute in this project, this is how to start contribute ( note: all PRs opened for GSSOC should point to the develop branch ) 
<!-- in detail -->

1. Fork the repo and while forking uncheck the box " Copy the master branch only " and it should be like this: <br>
   ![alt text](<Screenshot 2024-05-21 202707.png>)

2. After forking, clone the repo to your local machine.
To clone the repo to your local machine, run the following command in your terminal:
    
    ```bash
    git clone https://github.com/<your-github-username>/Dot-Box
    ```

3. Add a remote upstream to the original repo.
To add a remote upstream, run the following command in your terminal:
    
    ```bash
    git remote add upstream https://github.com/Durgesh4993/Dot-Box/
    ```

4. First, ensure you are on the `develop` branch.
To switch on `develop` branch.

   ```bash
   git checkout develop
   ```

5. Create a new branch.
To create a new branch, run the following command in your terminal:
    
    ```bash
    git checkout -b <your-branch-name>
    ```

6. Make changes in source code.

7. Add your changes
To add your changes, run the following command in your terminal:
    
    ```bash
    git add <File1 changed> <File2 changed> ...
    ```
8. Commit your changes.
To commit your changes, run the following command in your terminal:
    
    ```bash
    git commit -m "<your-commit-message>"
    ```

9. Push your changes.
To push your changes, run the following command in your terminal:
    
    ```bash
    git push origin <your-branch-name>
    ```

10. Create a PR and make sure your base branch is `develop`: <br>
 ![alt text](<Screenshot 2024-05-21 205520.png>)

__________________________________________________________________________________________________________________________________________________________________

## Alternatively Using GitHub Desktop

1. Open GitHub Desktop and log in to your GitHub account.

2. Make sure you are on the "Current Repository" view. If not, go to "File" and select "Add Local Repository" to add your repository.

3. In the "Current Repository" view, ensure you are on the branch `develop` to submit a pull request for. If you're not on the correct branch, use the "Branch" menu to switch to the correct branch.

4. Once you're on the correct branch, make your changes and commit them to the branch. You can do this by clicking the "+" button in the upper-left corner of the GitHub Desktop window, making your changes, and then entering a commit message.

5. After you've made your changes and committed them, click the "Push origin" button in the top-right corner of the GitHub Desktop window. This will push your changes to the remote repository on GitHub.

6. Now, go to the GitHub website, navigate to your fork of the repository, and you should see a button to "Compare & pull request" between your fork and the original repository, click on it.

7. On the pull request page, you can review your changes and add any additional information, such as a title and a description, that you want to include with your pull request. Make sure base branch is develop, that is `base:develop`

8. Once you're satisfied with your pull request, click the "Create pull request" button to submit it.

**Note:** In order to create a pull request, you must have a fork of the original repository in your GitHub account and you must have made the changes in that forked repository.

__________________________________________________________________________________________________________________________________________________________________

<!-- Open Source Programs -->
  <div>
    <h2><img src="https://github.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/blob/master/Emojis/Hand%20gestures/Flexed%20Biceps.png?raw=true" width="35" height="35" >Open Source Programs</h2>
  </div>

  This project is part of GirlScript Summer of Code. We welcome contributions from the community to help enhance Dot-Box.
  
![Community](https://github.com/GameSphere-MultiPlayer/Physi-c-Tech/assets/98798977/e79af9da-814e-487e-8a9a-85947384d3b2)

<hr>


<!-- Code of conduct -->
<div>
<h2><img src = "https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Handshake.png" width="35" height="35"> Code of Conduct</h2>
</div>

Please note that this project is released with a [Contributor Code of Conduct](.github/CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

<hr>

<!-- License -->
<div>
<h2><img src = "https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Page%20with%20Curl.png" width="35" height="35"> License</h2>
</div>

This project is licensed under the [MIT License](./LICENSE)

<hr>
 <!-- Cotributors -->
<div>
  <h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Red%20Heart.png" width="35" height="35"> Contributors</h2>
</div>

Thank you for contributing to our project! Your help is greatly appreciated in making Dot-Box even better. 😊

<center>
<a href="https://github.com/GameSphere-MultiPlayer/Dot-Box/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=GameSphere-MultiPlayer/Dot-Box" />
</a>
</center>
