# Building Blocks Game

Building Blocks Game is a fun, educational mobile game for kids. Players complete a building by dragging parts into place. Every two parts placed, a quiz pops up; answer correctly to continue, or the last two parts are removed. The game enhances problem-solving skills and knowledge with engaging animations and sound effects.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Running the Game](#running-the-game)
- [Contributing](#contributing)
- [License](#license)

## Features
- Drag-and-drop mechanics for building parts
- Quiz questions after every two parts placed
- Animations and sound effects for feedback
- Scoring system to track player progress

## Requirements
- [Unity](https://unity.com/) (version 2020.3 or higher recommended)
- [Git](https://git-scm.com/)

## Installation

### Clone the Repository
1. Open a terminal or command prompt.
2. Navigate to the directory where you want to clone the repository.
3. Run the following command:
    ```sh
    git clone https://github.com/your-username/building-blocks-game.git
    ```
4. Navigate to the project directory:
    ```sh
    cd building-blocks-game
    ```

### Open the Project in Unity
1. Open Unity Hub.
2. Click on the "Open" button.
3. Navigate to the cloned project directory and select it.
4. Unity will load the project. This may take a few minutes.

## Running the Game

### Play Mode in Unity Editor
1. Open Unity and load the project.
2. In the Unity Editor, open the `MainMenu` scene located in the `Assets/Scenes` folder.
3. Click the "Play" button at the top of the Unity Editor to run the game in Play Mode.

### Building the Game
To build the game for Android or iOS:

1. **Open Build Settings**:
    - Go to `File > Build Settings`.

2. **Select Platform**:
    - Select either `Android` or `iOS` from the list of platforms.
    - Click on `Switch Platform`.

3. **Add Scenes to Build**:
    - Ensure that the `MainMenu`, `Game`, and `EndScreen` scenes are added to the build. If not, click on `Add Open Scenes` to add them.

4. **Player Settings**:
    - Click on `Player Settings` to configure player settings such as icons, splash screens, etc.

5. **Build**:
    - Click on `Build` and choose a location to save the build.

6. **Deploy to Device**:
    - For Android: Transfer the APK file to your device and install it.
    - For iOS: Open the generated Xcode project and deploy it to your device.

## Contributing
Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
