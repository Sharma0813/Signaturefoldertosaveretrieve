✍️ Signature Saver & Retriever
A simple and functional Signature Save & Retrieve Web App built using HTML, CSS, and JavaScript.
Users can draw a signature on a canvas, save it as an image, and retrieve it later for reuse.

✨ Features
🖊️ Draw signature on canvas
💾 Save signature as an image file (PNG)
📤 Retrieve previously saved signatures
🧹 Clear canvas option
🎨 Clean, easy-to-use interface
📱 Fully responsive
⚡ Works fully in the browser — no backend required

🗂️ Project Structure
Signaturefoldertosaveretrieve/
├── index.html
├── style.css
└── script.js
Additional folders:
signatures/
└── saved-signature.png

🛠️ Technologies Used
HTML5 Canvas – Signature drawing
CSS3 – UI styling
JavaScript – Canvas logic, save & retrieve functions

🚀 Getting Started
Clone the Repository
git clone https://github.com/Sharma0813/Signaturefoldertosaveretrieve.git
cd Signaturefoldertosaveretrieve
Run the App
Open:
index.html
The signature pad will load instantly in your browser.

🖊️ How It Works
✔️ Drawing
User draws on an HTML <canvas> element
JavaScript tracks pointer/mouse events
✔️ Saving
The canvas is converted into an image using:
canvas.toDataURL("image/png")
That image is saved or downloaded

🙌 Acknowledgements
Created as a practical tool to understand HTML canvas, event handling, and client-side image export.


✔️ Retrieving

Previously saved signatures are loaded from a folder or from localStorage (depending on your implementation)
