# Snowflake Fractal Generator ❄️

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Algorithm](https://img.shields.io/badge/Algorithm-Recursion-red?style=for-the-badge)
![Turtle](https://img.shields.io/badge/Library-Turtle_Graphics-green?style=for-the-badge)

## 📖 Overview

This Python script visualizes the mathematical beauty of fractals by generating randomized snowflakes. It utilizes the **Turtle** graphics library and **Recursive Algorithms** to create self-similar geometric patterns.

## 💻 Technical Implementation

### Recursive Logic (`branch` function)
The core of the fractal generation lies in the `branch(size)` function.
-   **Self-Similarity**: The function iterates 3 times per branch section.
-   **Pattern**:
    1.  Move forward.
    2.  Move backward (backtracking).
    3.  Rotate (`right(45)`), creating the branching effect.
-   **Geometry**: The snowflake is constructed by repeating this recursive branch 8 times (`360 degrees / 45 degrees = 8 segments`) around a central point.

### Stochastic Generation
To simulate natural variety, the script uses the `random` module:
-   **Coordinates**: `random.randint(-200, 200)` places snowflakes arbitrarily on the canvas.
-   **Dimensions**: `sf_size` scales the base recursion depth.
-   **Aesthetics**: `random.choice(sfcolor)` selects from a predefined palette (White, Blue, Purple, Magenta).

### Turtle Configuration
-   **Speed**: Set to `15` (max speed) for efficient rendering.
-   **Background**: Cyan, providing high contrast for the white/bright snowflakes.

## 🚀 Execution

1.  Ensure Python 3.x is installed.
2.  Run the script:
    ```bash
    python sf1.py
    ```

## 🤝 Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## 👤 Author

**Simran Agarwal**
-   [Profile](https://github.com/officialsimranagarwal)
-   [LinkedIn](https://linkedin.com/in/simran-agarwal-54751b191)

---
*Generated with ❤️ by Simran Agarwal*
