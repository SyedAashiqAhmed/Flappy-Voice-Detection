# Flappy Bird with Voice Control

This is a simple Flappy Bird clone implemented in JavaScript, where the bird is controlled using voice input instead of keyboard or mouse controls.

## Features
- **Voice Control**: The bird jumps when detecting a loud enough sound through the microphone.
- **Dynamic Pipes**: Pipes are generated at random positions with a fixed gap.
- **Gravity & Collision**: The bird is affected by gravity and collides with pipes or the ground.
- **Score System**: Score increases as the bird successfully passes through pipes.
- **Game Over Screen**: Displays an image when the game is over and provides a restart button.

## How to Play
1. Allow microphone access when prompted.
2. Make a loud noise (like clapping or speaking loudly) to make the bird jump.
3. Avoid hitting the pipes or falling to the ground.
4. Keep playing to increase your score!

## Installation & Usage
1. Clone or download the repository.
2. Ensure all image assets (`flappybird.png`, `toppipe.png`, `bottompipe.png`, `qw.png`) are in the same directory as the script.
3. Open `index.html` in a web browser.

## Game Mechanics
- **Bird Physics**: The bird falls due to gravity and jumps when a sound is detected.
- **Pipe Generation**: Pipes appear at intervals with randomized heights.
- **Collision Detection**: The game ends when the bird collides with a pipe or the ground.
- **Score Calculation**: The score increases by 1 each time the bird passes a pair of pipes.

## Controls
- **Voice Input**: The bird jumps when a loud sound is detected.
- **Restart Button**: Click the "Restart" button to restart the game after losing.

## Dependencies
- Uses the Web Audio API for microphone input.
- Uses `requestAnimationFrame` for smooth game updates.

## Known Issues
- Microphone sensitivity may vary between devices.
- Browser permissions are required for microphone access.

## Future Improvements
- Adjustable microphone sensitivity.
- More interactive UI and animations.
- Mobile support and touchscreen controls.

## License
This project is open-source and can be modified or distributed freely.

