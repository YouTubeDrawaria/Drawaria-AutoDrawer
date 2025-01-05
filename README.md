# Drawaria AutoDrawer

Drawaria AutoDrawer is a Python-based application that automates the process of drawing images using mouse movements. Built with `tkinter` for the graphical user interface (GUI) and `pyautogui` for mouse automation, this tool is perfect for artists, hobbyists, or anyone interested in creating digital art programmatically.

---

## Features

- **Image Loading**: Load any image file (JPEG, PNG, etc.) and preview it in the application.
- **Image Customization**: Adjust image settings such as color channels (RGB), threshold, and resolution to create a custom drawing effect.
- **Drawing Automation**: Automate the drawing process by simulating mouse movements to trace the image on your screen.
- **Speed Control**: Control the speed of the drawing process with options like Fastest, Fast, Medium, and Slow.
- **Invert Image**: Invert the image colors for a different drawing effect.
- **Interruptible Drawing**: Stop the drawing process at any time using the `Esc` key.
- **Preview Mode**: Preview the final size and shape of the drawing before starting the automation.

---

## How It Works

1. **Load an Image**: Use the "Load Image" button to select an image file from your computer.
2. **Adjust Settings**: Customize the image using the available settings (e.g., color channel, threshold, resolution).
3. **Arm the Drawing**: Click the "Arm" button to prepare the application for drawing.
4. **Start Drawing**: Press the `Enter` key to begin the automated drawing process.
5. **Interrupt**: Press the `Esc` key at any time to stop the drawing process.

---

## Requirements

- Python 3.x
- Libraries: `tkinter`, `PIL` (Pillow), `pyautogui`, `numpy`, `keyboard`

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Drawaria-AutoDrawer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Drawaria-AutoDrawer
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   python autodrawer.py
   ```

---

## Usage

- **Load Image**: Click "Load Image" to select an image file.
- **Adjust Settings**: Use the sliders and dropdown menus to customize the image.
- **Arm Drawing**: Click "Arm" to prepare for drawing.
- **Start Drawing**: Press `Enter` to begin the automated drawing process.
- **Stop Drawing**: Press `Esc` to stop the drawing process at any time.

---

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Acknowledgments

- Thanks to the creators of `tkinter`, `Pillow`, `pyautogui`, `numpy`, and `keyboard` for their amazing libraries.
- Inspired by the need for a simple, automated drawing tool for digital artists.

---

Enjoy creating art with Drawaria AutoDrawer! 🎨