# Tower Defense Game (Java)

This project is a 2D Tower Defense game developed using Java and Swing, built around object-oriented programming principles and a custom game loop.

## Screenshots

![Gameplay](screenshots/gameplay.png)

## Game Overview

- Enemies follow a predefined path across the map.
- The player places defensive towers to stop incoming waves.
- Towers automatically detect and fire projectiles at enemies within range.
- Enemies have health bars and can be defeated before reaching the base.
- The game ends with a win or loss screen depending on wave survival.

## Project Structure

### Model
Contains core game entities and mechanics:
- `Enemy` classes (Dragon, Viking, etc.)
- `Tower` classes (Topcu, Okcu, BuzKulesi)
- `Bullet` classes (Mermi, Kule)
- Wave and collision logic

### View
Handles the graphical interface:
- `GamePanel` for rendering the map, towers, and enemies
- `KontrolPaneli` for tower selection and player controls
- `MainFrame` as the main application window

### Resources
Includes all sprites, tower images, projectiles, and map assets.

## Technologies Used

- Java
- Java Swing
- Object-Oriented Programming (OOP)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/EmreOuzouns/TowerDefense.git
   ```
2. Open the project in NetBeans or IntelliJ IDEA.
3. Run `MainFrame.java`.

## Notes

Developed to practice OOP design, game loop timing, and Java Swing GUI rendering.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
