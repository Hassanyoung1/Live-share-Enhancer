# Live Share Enhancer

## Overview
Live Share Enhancer is a Visual Studio Code extension designed to enhance the collaborative coding experience during Live Share sessions. The extension adds features like real-time code ownership tracking and provides a set of commands to improve productivity and streamline collaboration.

## Features
- **Real-Time Code Ownership Tracking**: Tracks changes made by participants during a Live Share session to promote accountability and better collaboration.
- **Session Event Notifications**: Displays notifications when a Live Share session starts or ends.
- **Command Integration**: Provides commands to start and stop the Live Share Enhancer within the editor.

## Requirements
- **Visual Studio Code**: Version 1.70.0 or higher
- **Live Share Extension**: Ensure the Visual Studio Code Live Share extension is installed and active.
- **Node.js**: Version 16 or higher

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/live-share-enhancer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd live-share-enhancer
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Build the extension:
   ```bash
   npm run compile
   ```
5. Launch the extension in Visual Studio Code:
   - Press `F5` to open a new VS Code window with the extension loaded.

## Usage
### Commands
The extension provides the following commands:
- **Start Enhancer**:
  - Command: `live-share-enhancer.start`
  - Description: Activates the Live Share Enhancer and displays a confirmation message.

- **Stop Enhancer**:
  - Command: `live-share-enhancer.stop`
  - Description: Deactivates the Live Share Enhancer and displays a confirmation message.

You can access these commands through the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

### Live Share Events
- When a Live Share session starts, you will see a notification: "Live Share session started."
- When a Live Share session ends, you will see a notification: "Live Share session ended."

## Development
### Project Structure
```plaintext
├── src
│   ├── extension.ts         # Main entry point for the extension
│   ├── features
│   │   └── codeOwnership.ts # Implements the code ownership tracking feature
├── out                      # Compiled output files
├── package.json             # Project metadata and dependencies
├── tsconfig.json            # TypeScript configuration
├── webpack.config.js        # Webpack configuration
```

### Scripts
- **Compile the Extension**:
  ```bash
  npm run compile
  ```
- **Watch for Changes**:
  ```bash
  npm run watch
  ```
- **Package for Distribution**:
  ```bash
  npm run package
  ```
- **Lint the Code**:
  ```bash
  npm run lint
  ```

### Debugging
1. Open the project in Visual Studio Code.
2. Press `F5` to start debugging.
3. A new VS Code window will open with the extension loaded.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push the changes to your fork:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## Known Issues
- Ensure the Live Share extension is installed and active to use the Live Share Enhancer.
- Compatibility issues may arise with older versions of Visual Studio Code or Node.js.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- **Visual Studio Live Share**: For providing a collaborative coding platform.
- **VS Code Extension API**: For enabling extension development.

## Contact
For questions or support, contact [hhassanhakeem@gmail.com]
