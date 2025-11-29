# Fibo-Snake Maze

Fibo-Snake Maze is a maze-based snake game where the player must navigate through a randomly generated maze, avoid enemy snakes, and solve Fibonacci number quizzes to score points.  
When you eat the correct answer, you move on to the next Fibonacci number.

This game combines:
- Classic snake movement  
- Randomly generated mazes  
- Multiple enemy snakes with independent AI movement  
- Fibonacci sequence quiz (1 → 1 → 2 → 3 → 5 → 8 → ...)  
- Ranking system with local score saving  

---

## 🎮 How to Play

### Move the Snake
- **Arrow Keys** on PC  
- **Swipe gestures** on mobile devices

Avoid:
- Walls  
- Enemy snakes  
- Incorrect numbers

Eat the **correct number tile** to advance to the next Fibonacci number and increase your score.

---

## 🧠 Fibonacci Quiz

Every time you eat the correct tile:

| Step | Fibonacci Number |
|------|------------------|
| 1 | 1 |
| 2 | 1 |
| 3 | 2 |
| 4 | 3 |
| 5 | 5 |
| 6 | 8 |
| ... | ... |

The next number is always  
**F(n) = F(n−1) + F(n−2)**

Four incorrect numbers appear randomly as traps.

---

## 📊 Difficulty Levels

You can choose from three difficulty settings:

### **Easy**
- Slow enemy snakes  
- Lower score multiplier  

### **Normal**
- Standard game balance  
- Normal maze complexity  

### **Hard**
- Fast enemy snakes  
- Higher maze complexity  
- Double score multiplier  

---

## 🏁 Game Over

You lose the game if:
- You hit a wall  
- You collide with an enemy snake  
- You eat a wrong number tile  

After the game, you can:
- Enter your nickname  
- Save your score locally  
- View rankings for each difficulty  

Rankings are stored in `localStorage` and saved on the same device/browser.

---

## 🧱 Maze Generation

Each playthrough creates a different maze using a depth-first search (DFS) algorithm with:
- Carved paths  
- Additional random openings  
- Clearing around cluster areas for playability  

This ensures unique gameplay every time.

---

## 🐍 Enemy Snakes (AI)

Three enemy snakes patrol the maze.  
Each one has:
- Its own speed depending on difficulty  
- Randomized direction changes  
- Collision detection with walls  

They act as moving obstacles the player must avoid.

---

## 📱 Mobile Friendly

- Responsive layout  
- Touch controls  
- Canvas automatically resizes  
- Works on smartphones and tablets  

---

## 📦 Technologies Used

- **HTML5 Canvas** (game rendering)  
- **JavaScript (ES6)**  
- **CSS3**  
- **LocalStorage** (ranking system)  

No libraries or frameworks required.

---

## ▶️ Running the Game

Simply open `index.html` in any modern browser:

- Chrome  
- Safari  
- Firefox  
- Edge  

No server setup needed.