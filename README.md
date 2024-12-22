# Solar-System-Animation

# Solar System Animation Project

A captivating Solar System simulation that demonstrates the orbit of celestial bodies around the Sun using **HTML**, **CSS**, and **JavaScript**. This project visually represents the planets Mercury, Venus, Earth, and its Moon, complete with animations.

---

## 🚀 Features

- **Realistic Orbits**: Smooth orbital animations for Mercury, Venus, Earth, and the Moon.
- **Dynamic Design**: Planets and the Sun are styled with realistic colors and shadows.
- **Responsive Layout**: Fully adaptable to different screen sizes for an optimal viewing experience.
- **Interactive Animation**: Uses CSS animations to simulate planetary movement.

---

## 🌟 Demo

Experience the beauty of the Solar System:

![Screenshot of Solar System Animation](screenshot.png)

---

## 📂 Folder Structure

```
project/
├── index.html     # Main HTML file
├── style.css      # Styles for the Solar System
```

---

## 🛠️ Installation

### Prerequisites

No special setup is required. Simply open the HTML file in a browser to view the animation.

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/solar-system-animation.git
   cd solar-system-animation
   ```
2. Open `index.html` in your browser to start the simulation.

---

## ✨ How to Use

1. Open the `index.html` file in any modern web browser.
2. Watch as the planets and the Moon orbit smoothly around the Sun.
3. Resize your browser window to see the responsive design in action.

---

## 🎨 Design Highlights

- **Black Background**: Represents the vastness of space.
- **Gradient Effects**: Smooth transitions and colors for celestial bodies.
- **Shadows and Highlights**: Enhances the 3D appearance of the Sun and planets.
- **Animations**: CSS keyframes are used to create smooth rotational effects.

---

## 🧩 Code Highlights

### Orbital Animation

```css
@keyframes orbit {
    to {
        transform: rotate(360deg);
    }
}

.earth {
    animation: orbit 37.5s linear infinite;
}
```

### Planet Design

```css
.earth::before {
    content: '';
    position: absolute;
    border-radius: 50%;
    top: 1.8em;
    right: 2.8em;
    width: 3em;
    height: 3em;
    background-color: aqua;
}
```

---

## 🤝 Contributing

We welcome contributions! Follow these steps:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## 💡 Acknowledgments

- Thanks to the open-source community for inspiration and tools.
- Inspired by the beauty and mystery of the Solar System.

---

## 📧 Contact

For any inquiries or feedback, please reach out to [your-email@example.com].
