# Tower Defense Game (Java)

This project is a 2D Tower Defense desktop game built in Java using Java Swing and object-oriented programming (OOP) principles. It was created to practice structuring a real-time game loop, managing entity lifecycles (enemies, towers, projectiles), handling collision detection, and separating game state from graphical rendering using a clean Model-View architecture.

In the game, waves of enemies follow a predefined path toward the player's base while the player places different types of defensive towers along the map. Each tower type has its own range, firing behavior, and projectile logic, automatically targeting enemies within range and reducing their health bars until they are defeated or reach the end of the path.

---

## Technical Overview

- **Model (`src/Model/`):** Defines the core entities and game mechanics, including `Enemy` classes (Dragon, Viking, etc.), `Tower` classes (Topcu, Okcu, BuzKulesi), `Bullet` classes (Mermi, Kule), wave progression, and collision checks.
- **View (`src/View/`):** Manages the Swing GUI components—`MainFrame` as the application window, `GamePanel` for rendering the map, sprites, health bars, and projectiles on a timer-driven game loop, and `KontrolPaneli` for tower placement and player controls.
- **Resources (`src/Resources/`):** Stores all 2D sprites, tower graphics, projectile assets, and map backgrounds.
- **How to Run:** Clone `https://github.com/EmreOuzouns/TowerDefense.git`, open the project in NetBeans or IntelliJ IDEA, and run `MainFrame.java`.

---

## Interface & Screenshots

### Gameplay View
Shows the map path, placed defensive towers, active enemy waves with health bars, and the side control panel.

![Gameplay](screenshots/gameplay.png)

### Win & Lose Screens
Displayed when the player survives all incoming waves or when enemies breach the base.

![Win Screen](screenshots/win-screen.png)
![Lose Screen](screenshots/lose-screen.png)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
