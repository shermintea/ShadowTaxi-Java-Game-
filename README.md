# ShadowTaxi
**A Java Taxi Game demonstrating Object-Oriented Programming and basic gameplay mechanics using the Bagel framework.**

---

## About the Project
ShadowTaxi is a 2D Java game where players navigate a taxi to pick up and drop off passengers while managing multiple screens (Home, Play Info, Gameplay, Game End).

This project was developed as a learning project to practice Java, object-oriented design, and basic game mechanics with university-provided assets.

Key features include:

- Home, Player Info, Gameplay, and Game End screens
- Keyboard controls for navigation and game flow
- Passenger pick-ups and trip tracking
- Simple scoring and win/loss conditions


---

## Built With

- **Java** - Core language for gameplay and logic
- **Bagel Framework** - For window management and game rendering
- **Properties Files** - For game configuration and localization

---

## Getting Started

### Prerequisites

- Java 17+
- Bagel framework(`bagel.jar` in your classpath)

### Running the Game

1. Clone the repository:
```bash
git clone https://github.com/shermintea/ShadowTaxi-Java-Game-.git
```

2. Navigate into the project directory:
```bash
cd ShadowTaxi-Java-Game-
```

3. Compile the Java files:
```bash
javac -cp "path/to/bagel.jar" src/*.java
```

4. Run the game:
```bash
   java -cp ".;path/to/bagel.jar" ShadowTaxi
```
Note: On Mac/Linux, replace `;` with `:` in the classpath.

---

## Project Structure
```bash
ShadowTaxi/
├── src/                # Java source files for gameplay, screens, and utilities
├── res/                # Resource files (properties, CSVs, credits)
├── README.md           # Project documentation
└── pom.xml             # Maven configuration
```

---

## Acknowledgements
- Bagel Framework - For providing an easy-to-use framework for 2D Java games.
- Inspired by Java coursework

---

## Optional Enhancements
- Add levels, difficulty, or scoring system.
- Improve graphics and animations.
- Add save/load functionality.


