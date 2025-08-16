# 💖 An Enchanted Birthday Journey 💖

A beautiful, single-file, animated website template to wish your loved ones a happy birthday in a memorable and magical way.

This project was originally created as a special birthday surprise for my sister, Shalmali, and has been turned into a template so you can share the magic too! It's designed to be super easy to personalize, even if you don't know how to code.

---

## ✨ Features

- **A Beautiful, Animated Journey:** The website unfolds like a story with smooth, scroll-based animations.  
- **Personalized Memory Lane:** Showcase your favorite photos in an elegant "scrapbook" style.  
- **Magical Wishes Wall:** A never-ending, floating shower of good wishes for the birthday person.  
- **Heartfelt Final Message:** A personal note that reveals itself with a dramatic typewriter effect.  
- **Interactive Easter Eggs:** Clickable floating hearts that pop with a cute sound effect!  
- **Background Music:** Includes a soft, cheerful background track with an easy mute/unmute button.  
- **Super Simple to Customize:** No coding required! Just edit one small section to add your own personal touches.  

---

## 🚀 How to Use

This template is designed to be as simple as possible! Here’s how to get started in just a few minutes.

### 1. Create Your Project Folder

Create a folder on your computer for the project. Inside, you'll need this structure:

```
Birthday Greeting/
├── index.html <-- This is the main file
└── assets/
├── images/ <-- Your photos go here
└── audio/ <-- Your song goes here
```

### 2. Add Your Photos and Music

- **Images:** Place all your favorite photos (landscape/horizontal photos work best!) inside the `assets/images/` folder.  
- **Audio:** Place your chosen `.mp3` song file inside the `assets/audio/` folder.  

### 3. Personalize the `index.html` File

Open the `index.html` file in any text editor (like Notepad, TextEdit, or VS Code).  
Right at the top of the `<script>` section (near the bottom of the file), you'll find the `config` area. This is the only part you need to edit!

```javascript
// =================================================================
// ======== CUSTOMIZATION SECTION: Edit these values! ========
// =================================================================
const config = {
    name: "Shalmali", // Change to the birthday person's name
    faviconEmoji: "🎂",
    greeting: "Happy Birthday,",
    subtitle: "Let's take a journey through some beautiful moments.",
    
    audioSrc: "./assets/audio/your-song-name.mp3", // Change to your song's file name
    audioArtist: "Artist Name", // Add the artist's name for credit
    audioSource: "Website Name", // Add where you got the song from
    
    photos: [
        { url: './assets/images/your-photo-1.jpg', caption: 'Your first caption here!' },
        { url: './assets/images/your-photo-2.jpg', caption: 'Your second caption here!' },
        // Add as many photos as you like!
    ],

    message: {
        p1: "Your first paragraph of the final message.",
        p2: "Your second paragraph of the final message.",
        signature: "With all my love,",
        from: "Your Name"
    },
    
    wishes: [
        "Your first wish here!",
        "Your second wish here!",
        // Add as many wishes as you like!
    ]
};

### 4. View Your Creation!

Because this project loads local files, you can't just double-click the `index.html` file to view it.  
The easiest way is to use the **Live Server** extension in a free code editor like VS Code:

1. Install VS Code and the **"Live Server"** extension.  
2. Open your project folder in VS Code.  
3. Right-click on `index.html` and choose **"Open with Live Server"**.  

Your beautiful, personalized birthday website will open in your browser! 🎉  

---

## ❤️ Credits & Final Note

This project was built with love and is meant to be shared. Feel free to use it, fork it, and make it your own.

- **Music:** The default track is *"Happy Birthday"* by WaveMaster from Pixabay. Please give credit if you use their music!  
- **Animations:** Powered by the amazing **GSAP** library.  

Enjoy spreading the birthday magic! ✨
