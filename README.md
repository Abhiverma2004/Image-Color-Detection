Color Detection App using OpenCV and Pandas
This is a simple Python project that allows users to detect colors in an image by double-clicking anywhere on the image. It displays the color name along with its RGB values.

<img src="https://i.imgur.com/WvQw2kL.png" alt="Color Detection Screenshot" width="600"/>
📁 Project Structure
graphql
Copy
Edit
color-detector/
│
├── colors.csv           # CSV file with color names and RGB values
├── PIC1.png             # Image to detect colors from
├── color_detector.py    # Main Python script
└── README.md            # Project documentation
✅ Features
Detect color names on double-click.

Shows RGB values of selected pixel.

Automatically displays text in black or white for better visibility.

Uses OpenCV and Pandas for fast color processing.

💡 Requirements
Python 3.x

OpenCV

Pandas

🚀 How to Run the Project
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/Abhiverma2004/color-detector.git
cd color-detector
Note: Replace your-username with your actual GitHub username (or whoever owns the repo).

2. Install Dependencies
Make sure you have Python installed. Then run:

bash
Copy
Edit
pip install opencv-python pandas
3. Add Your Files
Make sure PIC1.png is in the same directory.

Make sure you have colors.csv. You can find a sample here or use your own.

4. Run the App
bash
Copy
Edit
python color_detector.py
Double-click on any pixel in the image window to see the color name and RGB values.

Press ESC to close the app.

📦 Sample colors.csv Format
less
Copy
Edit
color,color_name,hex,R,G,B
red,Red,#FF0000,255,0,0
green,Green,#00FF00,0,255,0
blue,Blue,#0000FF,0,0,255
...
✨ Future Enhancements
Allow user to load any image at runtime.

Export selected color names.

Add support for hex values copy.

📜 License
This project is for learning purposes only.

