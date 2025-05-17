# ♟️ 3D Hartwig Chess Set

## 🎮 [Play Chess in Bauhaus Style](https://unanimousaditya.github.io/3D-Hartwig-Chess-Set/)

An interactive, 3D recreation of the iconic Josef Hartwig's Bauhaus chess set from 1924, built with **Three.js**. Experience the perfect union of form and function in this masterpiece of modernist design.

## 🏰 Description

This project brings to life the revolutionary chess set designed by Josef Hartwig at the Bauhaus school. Unlike traditional figurative chess pieces, Hartwig's design represents each piece through functional geometric forms that directly communicate their movement patterns. This digital recreation offers a fully playable chess experience with authentic 3D models based on the original 1924 design, celebrating one of the finest examples of the Bauhaus philosophy: "form follows function."

## ✨ Features

- 🎭 Faithful 3D models of all 32 chess pieces based on Hartwig's original Bauhaus design
- 🏁 Complete chess gameplay with standard rules
- 🖱️ Intuitive drag-and-drop interface for moving pieces
- 👁️ Multiple camera angles: player perspective, top-down, and free orbit
- 🔄 Piece rotation and board examination
- 💫 Subtle animations for piece movement, captures, and special moves
- 📱 Responsive design that adapts to different screen sizes
- 🎮 Game state tracking with move history and notation
- 🌓 Ambient lighting with realistic shadows and reflections
- 🎨 Authentic Bauhaus-inspired color scheme and materials

## 🕹️ Controls & Interaction

- 🔄 **Rotate View**: Click and drag (or swipe) to orbit around the board
- 🔍 **Zoom**: Scroll (or pinch) to zoom in and out
- 👆 **Select Piece**: Click or tap on any piece to select it
- 🚶 **Move Piece**: Drag selected piece to a valid square (highlighted)
- 📜 **View Move History**: Toggle the sidebar to see notation and captured pieces
- 🔧 **Settings**: Adjust camera settings, sound, and visual options
- ↩️ **Undo Move**: Take back the last move with the undo button
- 🔁 **Reset Board**: Start a new game at any time

## 💻 Technology Stack

- **Three.js** 🧊 - JavaScript 3D library for rendering the chess set and board
- **HTML5** 📝 - Structure and canvas elements
- **CSS3** 🎨 - Bauhaus-inspired styling and responsive design
- **JavaScript** ⚙️ - Chess game logic and user interaction:
  - Chess rules enforcement
  - Move validation
  - Game state management
  - Animation control

## 🧪 Technical Implementation Details

- **Authentic Models** - Precisely recreated 3D models based on Hartwig's original designs
- **Chess Logic** - Full implementation of chess rules including castling, en passant, and promotion
- **Material Design** - PBR materials that mimic the wood and finish of the original set
- **Raycasting** - Precise piece selection and movement using Three.js raycasting
- **Optimized Rendering** - Performance enhancements for smooth play on all devices
- **State Management** - Robust tracking of game state with FEN notation support

## 🏛️ The Bauhaus Connection

Josef Hartwig designed this chess set in 1924 at the Bauhaus school, where form and function were unified. Each piece's shape represents its movement pattern:
- **Pawns**: Simple cubes that move in one direction
- **Rooks**: Square blocks representing linear movement
- **Knights**: L-shaped pieces showing their unique movement pattern
- **Bishops**: Diagonal crosses indicating their movement along diagonals
- **Queen**: Sphere + cube combining the movement abilities of rooks and bishops
- **King**: Cross on top of a cube symbolizing its limited but multidirectional movement

This digital recreation honors the Bauhaus principle that the form of an object should be determined by its function, creating a chess set where the pieces' shapes directly communicate how they move.

## ⚡ Installation

To run the chess set locally:

1. 📂 Clone the repository:
   ```bash
   git clone https://github.com/unanimousaditya/3D-Hartwig-Chess-Set.git
   ```

2. 📁 Navigate to the project directory:
   ```bash
   cd 3D-Hartwig-Chess-Set
   ```

3. 🌐 Set up a local server:
   - Using Python 3:
     ```bash
     python -m http.server
     ```
   - Using Node.js:
     ```bash
     npx serve
     ```

4. 🎲 Open your browser and go to `http://localhost:8000` or the port specified by your local server

## 📚 Code Structure

- `index.html` - Main HTML document containing the canvas and UI elements
- `css/main.css` - Styling for the user interface and controls
- `js/main.js` - Core application logic and Three.js initialization
- `js/ChessGame.js` - Chess rules and game state management
- `js/ChessPieces.js` - 3D models and piece behavior
- `js/ChessBoard.js` - Board layout and square selection logic
- `js/CameraControls.js` - Camera positioning and movement
- `models/` - 3D models for chess pieces
- `textures/` - Material textures for wood, board, and pieces
- `sounds/` - Audio effects for piece movement and captures

## 🎨 Customization Options

You can easily modify different aspects of the chess set:

- 🎭 **Alternative Materials** - Change the materials to different woods or modern materials
- 🌈 **Color Schemes** - Switch between classic Bauhaus colors or create custom themes
- 🏠 **Board Designs** - Implement different chessboard styles and materials
- 🎞️ **Animation Styles** - Adjust movement animations and visual effects
- 🎵 **Sound Effects** - Add custom sounds for different pieces and actions

## 🤝 Contributing

Contributions are warmly welcomed! If you'd like to enhance this modernist chess experience:

1. 🍴 Fork the repository
2. 🌿 Create a new branch (`git checkout -b feature/amazing-chess-feature`)
3. ✏️ Make your design-inspired changes
4. 💾 Commit your changes (`git commit -m 'Add some amazing chess feature'`)
5. 📤 Push to the branch (`git push origin feature/amazing-chess-feature`)
6. 🔁 Open a Pull Request describing your enhancements

### 💡 Enhancement Ideas
- Add AI opponent with multiple difficulty levels
- Implement online multiplayer functionality
- Create an AR version for mobile devices
- Add animations showing possible moves for selected pieces
- Develop a tutorial mode explaining the Bauhaus design principles

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎨 Design Accuracy Note

This digital recreation strives to maintain the authentic proportions and spirit of Josef Hartwig's original 1924 design while adapting it for interactive digital play. The materials, colors, and forms closely follow the Bauhaus aesthetic and philosophy.

## 👏 Acknowledgments

- 🏛️ Josef Hartwig and the Bauhaus school for the original revolutionary chess design
- 🏆 The Museum of Modern Art (MoMA) for preserving and documenting the original set
- 🙏 Created with passion by [Aditya Raj](https://github.com/unanimousaditya)
- 📚 Special thanks to the Three.js community for support and inspiration

## 📞 Contact

- 👨‍💻 GitHub: [@unanimousaditya](https://github.com/unanimousaditya)

---
♟️ Experience the elegance of Bauhaus design while playing the timeless game of chess! Don't forget to star ⭐ the repo if you enjoyed this modernist interpretation!
