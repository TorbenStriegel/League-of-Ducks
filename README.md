# League of Ducks

![LeagueOfDucks](https://github.com/TorbenStriegel/League-of-Ducks/assets/29056807/73329ba5-75e5-40cf-bc23-2c45f8c14397)

## Introduction
"League of Ducks" is a casual jump-and-run game where the goal is to defeat all other players (ducks) and be the last one standing. The game consists of multiple rounds, and the player with the highest score at the end of the game wins. We developed this project using the Unity development environment and the Photon Network Engine. Currently, the game is available for Android devices (version 4.0.3 and up), Windows computers (Windows 7+ and .NET Framework 3.5+), and as an HTML5 version (for modern browsers in beta stage). The project is designed to be cross-platform, allowing players on different devices to play together seamlessly. The game logic is primarily written in C#.

![game](https://github.com/TorbenStriegel/League-of-Ducks/assets/29056807/b9181a33-7739-4a5e-a692-652cc29996a8)

![UI](https://github.com/TorbenStriegel/League-of-Ducks/assets/29056807/d3b86100-1d79-4fc1-bccd-d247a895bf86)

You can find more information in the [documentation](https://github.com/TorbenStriegel/League-of-Ducks/files/12871776/Doku_LeagueOfDucks.pdf)

## Getting Started
Here's how to get started with the game:

### Unity
Unity is a powerful game development platform that allows you to create 2D, 3D, augmented reality, and virtual reality games. To set up Unity, follow these steps:
1. [Download Unity](https://unity.com/).
2. Install Unity by following the installation instructions on the Unity website.

### Game Installation
To play the game on different platforms, follow the links below:
- [Android App](https://play.google.com/store/apps/details?id=de.CloudStudios.LeagueofDucks)
- [PC Version (Windows)](https://drive.google.com/file/d/1e2ZY0T9lDxZnmNvmr8V1CU6E2n0gGEhf/view?usp=sharing)
- [Web Version (with PC controls)](http://cloudstudios.ddns.net/CT/PC/)
Please note that the controls vary slightly between platforms, but there are no other differences in gameplay.

## Gameplay
- Your objective is to achieve the highest possible score.
- You gain points for winning each round (200 points per win).
- Falling down or getting hit by an opponent results in point deductions (-20 points).
- Each player starts with three lives and a weapon.
- You can't regenerate lost lives.
- There are four different weapons, each with varying strength, range, and ammo count.
- To obtain a better weapon, pick it up at designated weapon spawns.
- You can switch your view to a camera that provides an overhead view of the entire map.
- You have a double jump ability and can perform wall jumps.

![andoid](https://github.com/TorbenStriegel/League-of-Ducks/assets/29056807/abe49038-76a0-4015-b842-4616abb4245f)

## Class Structure
- **DuckInfo:** Manages multiplayer functionality and synchronizes game elements.
- **Steuerung (Controls):** Handles player movement, including running and jumping.
- **WeaponManager:** Manages the various weapons and ensures the correct image is displayed.
- **Weapon:** An abstract class representing different weapon types. Subclasses represent each weapon.
- **Ammo:** Subclasses of Weapon that define ammunition for each weapon.
- **Bullet:** An abstract class that controls bullet trajectories and lifespan. Subclasses define different bullet types.

![Bild1](https://github.com/TorbenStriegel/League-of-Ducks/assets/29056807/79e67cf8-995e-4c8c-9ffd-9f325ebf7ec9)

## Conclusion
"League of Ducks" presented us with new challenges that our team successfully overcame. We applied our past experiences from previous projects to create a game that offers both challenges and enjoyment. In hindsight, this project was a success, and working on it as a team was a fun and rewarding experience. We look forward to applying the knowledge gained from this project to future endeavors.
