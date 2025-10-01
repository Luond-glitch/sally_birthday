# 🎂 Happy 21st Birthday Web Page

This is a special **interactive birthday webpage** built with **HTML, CSS, and JavaScript**.  
It includes animations, a 3D image carousel, floating hearts, confetti effects, a music player, and a surprise popup modal.

---

## 🌟 Features

- **Popup Modal**  
  A sweet popup appears first with a heartfelt message and "YES/NO" buttons.  
  - Clicking **YES** unlocks the main celebration page with music, images, and animations.  
  - Hovering over **NO** makes the button run away playfully.  

- **3D Image Carousel**  
  - Displays a circular rotating photo gallery.  
  - Each image is fitted inside its frame using `object-fit: contain`.  
  - Broken images fall back to a placeholder.

- **Floating Hearts Background**  
  - Randomly placed animated hearts float in the background.  
  - Creates a dreamy and romantic mood.

- **Confetti Effect**  
  - On clicking **YES**, colorful confetti rains down the screen.

- **Music Player**  
  - A background "Happy Birthday" song starts playing automatically.  
  - A floating player lets you play/pause the track.

- **Responsive Design**  
  - Works smoothly on both desktop and mobile devices.

---

## 📂 Project Structure

birthday-project/
│
├── index.html # Main HTML file
├── /images # Folder containing birthday photos
├── README.md # Project documentation

Copy code

---

## 🖼️ Image Setup

1. Place all your images inside the `/images` folder.  
2. Update the **image paths** in the `imagePaths` array inside `index.html`:

```javascript
const imagePaths = [
    'images/photo1.jpg',
    'images/photo2.jpg',
    'images/photo3.jpg'
];
🎶 Music Setup
The project uses a sample "Happy Birthday" track from Mixkit.

You can replace it by editing the <audio> tag in index.html:

html
Copy code
<audio id="backgroundMusic" loop>
    <source src="your-song.mp3" type="audio/mpeg">
</audio>
🚀 How to Run
Download or clone this repository.

Open index.html in your browser.

Enjoy the birthday surprise! 🎉

📌 Customization
Colors & Gradients → Adjust inside the body and .modal-content CSS.

Messages → Edit the modal text and the birthday message section in HTML.

Animations → You can tweak carousel speed and heart/confetti count in JavaScript.

❤️ Credits
Music: harmonize birthday song

Icons & Emojis: Unicode Standard

Code: Custom HTML, CSS, and JavaScript

🎁 Preview
Here’s what you’ll see:

A popup modal with a question.

If YES, the page reveals a rotating photo carousel, birthday message, confetti, and background music.

If NO, the button runs away! 😄
