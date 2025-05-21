# 🏠 3D Creative Room - Pure CSS Art

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

<div align="center">
  <img src="preview.gif" alt="3D Room Preview" width="600px">
  <p><i>An interactive 3D room created with pure CSS - no WebGL or 3D libraries</i></p>
</div>

## ✨ Features

- **Pure CSS 3D Environment** - No 3D libraries or WebGL needed
- **Fully Interactive** - Explore the room from different angles
- **Detailed Components** - Bookshelf, television, couch, pictures, and more
- **Responsive Design** - Adapts to different screen sizes
- **Ambient Lighting Effects** - Simulated room lighting with CSS
- **Minimal JavaScript** - Only used for handling interactions

## 📋 Project Structure

```
3D-ROOM-PURE-CSS-ART/
├── .godo/              # Project configuration files
├── index.html          # Main HTML structure
├── index.pug           # Pug template (if using Pug for HTML)
├── main.js             # JavaScript for interactions
├── style.css           # Main CSS styles
└── style.scss          # SCSS source (if using Sass)
```

## 🔍 How it Works

This project leverages advanced CSS techniques including:

- **3D Transforms** - Using perspective, rotateX/Y/Z and translate3d
- **CSS Custom Properties** - For dynamic style manipulation
- **Nested 3D Spaces** - Creating complex multi-layered 3D objects
- **Shadow Techniques** - For realistic lighting effects

Each component in the room is built using the 6-face cube technique where each face (front, back, left, right, top, bottom) is positioned to create a 3D object.

## 🛠️ Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML and CSS

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sadat-Rakib/3D-Creative-Room---Pure-CSS-Art.git
   cd 3D-Creative-Room---Pure-CSS-Art
   ```

2. Open `index.html` in your browser:
   ```bash
   # Using Python's built-in server
   python -m http.server
   # Or simply open the file in your browser
   ```

## 🎮 Usage & Interaction

- **Mouse Movement**: Move your cursor across the room to change perspective
- **Mobile**: Use device orientation for a responsive 3D experience

## 🧩 Key Components

The room features several detailed 3D components:

- Bookshelf with individual books
- Television with screen
- Couch with cushions
- Coffee table
- Picture frames
- Decorative items
- Ambient lighting
- Door with frame

## 📱 Responsive Design

The room adapts to different screen sizes while maintaining the 3D effect:

- **Desktop**: Full interactive experience
- **Tablet**: Optimized perspective
- **Mobile**: Touch-friendly interactions

## 🧠 Technical Implementation

The project uses a cube-based approach for all 3D objects:

```css
.object {
  transform-style: preserve-3d;
  position: absolute;
}

.face {
  position: absolute;
  backface-visibility: hidden;
}
```

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Inspiration from modern interior design
- CSS 3D transform techniques
- The growing community of CSS artists

## 📬 Contact

Project Link: [https://github.com/Sadat-Rakib/3D-Creative-Room---Pure-CSS-Art](https://github.com/Sadat-Rakib/3D-Creative-Room---Pure-CSS-Art)

---

<div align="center">
  <p>⭐ Star this repository if you found it interesting! ⭐</p>
  <p>Made with ❤️ and pure CSS</p>
</div>
