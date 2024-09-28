# Flappy Game

This project is a simple web-based game inspired by the classic **Flappy Bird**. Built using **HTML5**, **JavaScript**, and **Tailwind CSS**, this game allows the player to control a bird by clicking or pressing the spacebar to make it "flap" and avoid obstacles (pipes). The player can also upload a custom bird image to personalize the game.

## Demo

You can play the game by visiting the deployed GitHub Pages site:  
[Flappy Game](https://fatihyuksel3109.github.io/flappy-bird/)

## How to Play

1. **Objective**: Guide the bird through the gaps between the pipes without colliding.
2. **Controls**:
   - **Click on the screen** or **press the spacebar** to make the bird "flap" and go up.
   - The bird will naturally fall due to gravity, so time your flaps to keep it in the air.
3. **Score**: Every time you successfully pass between two pipes, your score increases by 1.
4. **Game Over**: The game ends if the bird hits the pipes or the ground. Click or press the spacebar to restart the game.

### Customize Your Bird

- You can upload a custom image for the bird by clicking the **"Choose File"** button and selecting an image from your computer.

## Features

- **Dynamic Controls**: The bird can be controlled by both mouse click and spacebar.
- **Custom Bird Images**: Players can upload their own bird images.
- **Random Pipe Generation**: Pipes are randomly generated with varying gaps.
- **Simple Scoring System**: The score is displayed and increases as you pass through pipes.
- **Game Over**: A notification and restart option appear when the player hits an obstacle.

## Technologies Used

- **HTML5**: Canvas is used to render the game.
- **JavaScript**: Core game logic and event handling.
- **Tailwind CSS**: For styling and layout.

## File Structure

```bash
.
├── index.html         # Main HTML file with embedded JavaScript and Tailwind CSS
├── README.md          # Project documentation
```

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/fatihyuksel3109/flappy-bird.git
   ```
2. Open the `index.html` file in your web browser to start playing the game.

## Deployment

If you want to deploy this game using GitHub Pages:
1. Rename the `index.html` file (if not already named).
2. Push your changes to GitHub.
3. Navigate to your repository's **Settings** > **Pages**, and select the `main` branch for deployment.
4. The game will be available at `https://yourusername.github.io/repository-name/`.

## Customization

- **Gravity and Jump Strength**: Modify the values of `gravity` and `jumpStrength` in the JavaScript code to adjust the game's difficulty.
- **Pipe Settings**: Change `pipeWidth`, `pipeGap`, and `gameSpeed` to customize the appearance and speed of the pipes.

## License

This project is licensed under the MIT License.

---

You can replace `yourusername` and `repository-name` with your actual GitHub username and repository name. Add a screenshot of the game (as `screenshot.png`) to make the README more visual.
