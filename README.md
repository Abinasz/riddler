# ❓ The Riddler's Terminal (The Batman)

website: https://arkhamintiative.vercel.app/

> *"Hello Vengeance... Eager to learn the locations, my little anarchy?"*

This is an immersive, retro-styled interactive web terminal inspired by **The Batman (2022)**. Built with HTML, Tailwind CSS, and vanilla JavaScript.
----------------------------------------------------------------------------------------------------------------------------------------------------------

## Features

* **Cinematic Intro Sequence:** Typewriter text effects with dynamic cursor blinking and smooth text-deletion animations matching the Riddler's communication style.
* **Web Audio API Sound FX:** Custom-synthesized soft mechanical keyboard click sounds on every typed character, plus a high-pitched bomb activation alarm beep on incorrect answers.
* **Punishment System:** Getting a riddle wrong triggers a crimson red system alert (`CRUOR EST IN MANU TUA`) accompanied by stock explosion footage.
* **System Termination Protocol:** Successfully answering all four riddles initiates a violent terminal glitch sequence before permanently disconnecting the session.
* **CRT Retro Aesthetic:** Built-in scanlines, custom glow shadows, and dark console styling.

---

## Project Structure

```text
riddler/
│
├── index.html       # Main application (HTML, Tailwind CSS, & JavaScript logic)
└── assets/          # Stock explosion videos for wrong answers
    ├── explosion1.mp4
    ├── explosion2.mp4
    ├── explosion3.mp4
    └── explosion4.mp4
