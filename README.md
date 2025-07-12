# 🕵️‍♀️ Image Steganography Tool (Python GUI Project)

This project is a simple **Image Steganography Tool** built using Python. It allows users to **hide (embed)** secret text messages inside images and **extract** them later. The GUI is designed using Tkinter, and image processing is handled using Pillow and Stepic libraries.

---

## 📌 Project Highlights

- ✅ Embed secret messages in PNG/BMP images
- ✅ Extract hidden messages anytime
- ✅ Lightweight, GUI-based desktop tool
- ✅ Clear success/error pop-ups using Tkinter's `messagebox`

---

## 🔧 Tools & Technologies Used

| Tool/Library  | Purpose                          |
|---------------|----------------------------------|
| Python 3      | Core programming language        |
| Tkinter       | GUI development                  |
| PIL (Pillow)  | I
steganography_tool/
├── steganography_gui.py # Main GUI Python script
├── original.png # Input image (user selected)
├── secret_output_final.png # Output image with message
├── README.md # Project documentation

---

## 🚀 How to Run

> Ensure you have Python installed. Stepic and Pillow can be installed via pip:

```bash
pip install stepic Pillow
Steps:
Navigate to the folder:

bash
Copy
Edit
cd Desktop/steganography_tool
Run the GUI:

bash
Copy
Edit
python steganography_gui.py
Use the GUI:

Select an image (.png or .bmp)

Enter the secret message

Choose a save location for the new image

Click Embed Message or Extract Message
Project Status
🟢 Completed

GUI and core functionality are working.

Tested with multiple PNG images.

Readable outputs and user-friendly alerts.
Learning Outcome
Steganography fundamentals

Tkinter GUI development

Handling file dialogs and image processing

Embedding messages without altering image visibly

Contact
Created as part of a cybersecurity practical project
📧 Author: [UPASNA]
📅 Date🕦 July 2025
