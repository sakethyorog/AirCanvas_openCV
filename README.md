# AirCanvas_openCV

AirCanvas_openCV is an interactive computer vision project built using OpenCV that allows users to draw in the air using hand movements or a colored object. The application tracks color markers through a webcam and creates a virtual canvas where users can paint in real time.

---

## 🚀 Features

### 🎨 **Air Drawing**
Draw in the air by showing a colored object (pen cap, marker, etc.) to your webcam. The application will track motion and convert it into strokes on a virtual canvas.

### 🖌️ **Multiple Brush Colors**
The following color options appear on the screen:
- Blue  
- Green  
- Red  
- Yellow  

Tap on the respective color box on the screen to switch brush color instantly.

### 🧹 **Clear Canvas**
A **CLEAR** button is displayed at the top of the screen.  
Click/tap on it anytime to wipe the canvas clean.


### ⚡ **Auto Clean Feature**
An automatic cleaning function periodically resets the canvas to avoid clutter or unwanted strokes.

---

## 🛠️ Technologies Used

- **Python**
- **OpenCV**
- **NumPy**
- Webcam input for real-time video tracking

---

## 📦 Installation

Follow the steps to run this project locally:

```bash
# Clone the repository
git clone https://github.com/sakethyorog/AirCanvas_openCV.git
cd AirCanvas_openCV

# (Optional) Create Virtual Environment
python -m venv .venv

# Activate Environment
# Windows:
.venv\Scripts\activate
# macOS / Linux:
source .venv/bin/activate

# Install Dependencies
pip install -r requirements.txt
