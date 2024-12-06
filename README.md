# **Maze Muncher** 🎮🍒

Prepare yourself for a **maze-filled adventure** with a twist! In **Maze Muncher**, you'll guide our fearless yellow hero through a labyrinth of pellets, outmaneuver ghosts with questionable ethics, and prove your mastery of the munch! 🎩

## **Overview**

Welcome to **Maze Muncher**, an interactive web-based game that brings back arcade nostalgia with a dash of modern creativity. Navigate through a maze, dodge those sneaky ghosts, and clear the board of pellets for a well-deserved victory. Whether you’re a casual gamer or a hardcore muncher, this game offers something for everyone.

- **Simple Controls:** Easy arrow-key navigation to glide through the maze.
- **Dynamic Gameplay:** Tailored difficulty levels—because we believe in making everyone suffer (at their own pace).
- **Background Music:** Nostalgic tunes to make munching an auditory treat.

## **Features**

### 🟡 **Arcade Nostalgia with a Twist**
- Smooth navigation in a retro-inspired maze.
- Collect pellets and avoid the cunning ghosts at all costs.

### 👻 **Ghostly Pursuers**
- Adaptive ghosts that adjust their paths to hunt you down.
- The higher the difficulty, the scarier (and faster) they get. Run!

### 🎵 **Immersive Soundtrack**
- Background tunes to set the perfect mood. 
- Get lost in the music (but don’t lose focus on the ghosts).

### 🎮 **Custom Difficulty Levels**
- **Easy:** One ghost—perfect for warming up your munching skills.
- **Medium:** Two ghosts—because life isn’t always easy.
- **Hard:** Three relentless ghosts that question your every life decision.

### 🎯 **Responsive Design**
- Optimized for all modern browsers.
- Sleek and intuitive interface for seamless gameplay.

---

## **Game Preview**

### Main Gameplay:
![Game in action](![Screenshot 2024-12-06 130943](https://github.com/user-attachments/assets/671f133c-8590-4719-8b3b-73a968e24ad3)
)

### Game Over (Oops!):
![Game Over](![Screenshot 2024-12-06 131225](https://github.com/user-attachments/assets/3b49cb1a-c287-4078-8558-dd22fd6bd36c)
)

### Difficulty Selector:
![Difficulty Selection](![Screenshot 2024-12-06 131243](https://github.com/user-attachments/assets/31eaf142-a576-4e29-86f2-edb7abbf5154)
)

---

## **How to Play**

1. **Get Started:**
   - Select your desired difficulty from the dropdown menu.
   - Click **Start Game** and jump straight into the maze.
   - Use **arrow keys** to control your hero.

2. **The Goal:**
   - Clear all pellets from the maze.
   - Avoid ghosts at all costs (they’re not as friendly as they look).

3. **Game Over:**
   - A ghost touches you? It's all over. Click **Try Again** and show those ghosts who’s boss.

4. **Victory:**
   - Successfully clear the board of pellets to win the game.

---

## **Installation**

Follow these steps to enjoy **Maze Muncher** on your local machine:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Norah-G/CompGraphicsProject.git
   cd CompGraphicsProject
   ```

2. **Open the Game**
   - Locate the `index.html` file in your directory.
   - Open it in your favorite browser (or whatever browser you’re stuck with). 

3. **Optional Local Server**
   - For advanced users, serve the game using:
     - Python:
       ```bash
       python -m http.server
       ```
---

## **Controls**

- **Arrow Keys:** Navigate through the maze:
  - ⬆️: Move Up
  - ⬇️: Move Down
  - ➡️: Move Right
  - ⬅️: Move Left

- **Mouse:**
  - Use buttons to start or restart the game.
  - Select difficulty from the dropdown menu.

---

## **How It Works**

### Game Elements
1. **Maze:**
   - The game maze is structured as a grid (15x20 cells), built using a 2D array (`MAZE`).
   - Walls (`1`) block your path, while clear routes (`0`) let you move freely.

2. **Pellets:**
   - Scattered across the maze at the start of the game.
   - Each pellet increases your score.

3. **Ghosts:**
   - Programmed to chase you using adaptive algorithms.
   - Their speed and count vary based on the selected difficulty.

4. **Maze Hero (aka You):**
   - Moves continuously in the chosen direction.
   - Cannot pass through walls (because physics, duh).

### Technical Details
- **Canvas API:** Handles the rendering of the maze, Pac-Man, ghosts, and animations.
- **JavaScript Classes:** Simplifies ghost logic and pellet behavior.
- **Audio API:** Provides seamless background music for immersive gameplay.

---

## **Tips and Tricks**

1. **Stay Ahead of the Ghosts:**
   - Always plan your moves. Ghosts are faster than you think.

2. **Corner Strategy:**
   - Use corners to throw ghosts off their path.

3. **Master Easy Before Moving Up:**
   - Learn the maze and ghost behavior on Easy mode before trying Medium or Hard.

4. **Be Persistent:**
   - Ghosts may get you, but they can’t stop you from hitting that **Try Again** button.

---

## **Contributing**

Want to add power-ups, new mazes, or more devious ghosts? Join the **Maze Muncher** project!

1. Fork the repository.
2. Create a branch for your changes:
   ```bash
   git checkout -b feature/new-feature
   ```
3. Commit and push your changes:
   ```bash
   git commit -m "Added new maze"
   git push origin feature/new-feature
   ```
4. Submit a pull request, and let’s make this game even more epic.

---

## **Acknowledgments**

- **The Original Maze Legends:** For inspiring generations of maze gamers.
- **JavaScript & Canvas API:** For making browser-based creativity possible.
- **Music.js Creators:** For adding life to this munch-tastic adventure.

---

### 🚀 **Ready to Munch?**
*"Side effects include ghost-dodging reflexes and an unhealthy obsession with yellow circles."* 🟡  
Go ahead—**hit Start and get munching!** 🎮 
