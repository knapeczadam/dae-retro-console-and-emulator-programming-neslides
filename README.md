# 🕹️ Retro Console & Emulator Programming – NESlides 

Hey there, fellow DAE student, curious visitor, or retro enthusiast 👋  
Welcome to our **Retro Console & Emulator Programming** repository — a showcase of what we built during the **third semester (2024)** at **DAE**.

---

## 🗄️ About this repository

This repo contains our **NES homebrew project**, fully written in **6502 Assembly**.  
The result is an interactive “presentation” app — **NESlides** — where the player can navigate between slides and shoot every tile on screen, completely erasing the slide if they wish.

It’s a playful experiment that merges **low-level programming**, **hardware constraints**, and a touch of chaos.

## Requirement to play

- Mesen or any other emulator for NES
- Controller

### Requirement to compile

- Make
- CC65 compiler

## Running the Game

To run the game simply download the latest release [here](https://github.com/knapeczadam/dae-retro-console-and-emulator-programming-neslides/releases/tag/1.0.0) and run the `NESlides\out\NESlides.nes` with [Mesen](https://www.mesen.ca).

To play the game load the `.nes` file with an Emulator like Mesen. You will need a controller to play.

#### Controls

| Control           | Action                       |  
|-------------------|------------------------------|  
| **D-PAD**         | Move / Change Selection      |  
| **SELECT**        | Confirm Selection            |  
| **X & A**         | Change Audio                 |  
| **START**         | Cahnge Color Palett          |  
| **Y & B**         | Shoot                        |  

**AUDIO WARNING** The audio starts on max volume so be careful when playing it with headphones!
* `X & A` are west and south buttons, if you are using a different controller.
* `Y & B` are north and east buttons, if you are using a different controller

## Compiling the Project from source

Before compiling you will need a `cc65 compiler` which you can find [here](https://github.com/cc65/cc65/releases/tag/V2.19). 
Download the latest source code version. Unzip it and rename it to "cc65" then move it to the `C:\` folder.

Then download this project's code from the top right corner and Unzip when downloaded.

Open the Command Prompt using `Win + R` and typing `cmd` or by searching for command prompt.
Then navigate to the folder you just downloaded.

```cmd
cd C:\ProjectDirectory

in my case

cd C:\Users\me\Downloads\NESlides-main
```

You can make this step easier by copying the path from the explorer.

Finally type 

```cmd
make clean && make all
```

you can now find in `ProjectDirectory\out` a file called `NESlides.nes` which you can load in Mesen.

---

## 🔎 Course Information

**📚 Course:** Retro Console & Emulator Programming  
**🏫 University:** Howest University of Applied Sciences - Digital Arts and Entertainment   
**📍 Location:** Kortrijk, Belgium  
**🗓️ Academic year:** 2024–25 | Third semester  
**🎓 Study load:** 6 credits  
**⏱️ Total study time:** 180 hours  

---

## 👨‍🏫 Teaching Staff

- **Co-ordinator:** Tom Tesch  

---

## 👥 Team Members

- Dylan Burgisser  
- Jakub Fratczak  
- Ádám Knapecz  
- Tuur Martens  

---

## 🎯 Learning Goals

- Solves **technical problems** using a suitable programming language.  
- Creates **prototypes** based on **mathematical algorithms** (specific to Game Development).  
- Follows **programming conventions** to produce structured, readable, and maintainable code.  
- Identifies and **debugs errors** in existing or newly written code.  

---

## 🧩 Course Content

- **Understanding Vintage Consoles**  
  - Study the architecture and design of classic **8-bit gaming consoles**.  
  - Explore how **hardware components**, **memory management**, and **CPU limitations** shaped early game development.  
  - Analyze historical **engineering trade-offs** and **system design decisions**.  

- **Assembly Programming Project**  
  - Develop a **small game or tool** in **assembly language** targeting the studied console.  
  - Gain hands-on experience with **low-level programming**, **manual memory handling**, and **CPU cycles**.  
  - Work collaboratively in teams to build efficient and functional software within strict hardware constraints.  

- **Enter C++**  
  - Transition from assembly to **C++**, exploring how higher-level languages interact with hardware.  
  - Choose between:  
    - Building a **C++ emulator** capable of running the previously developed assembly program.  
    - Setting up a **toolchain** to generate identical binaries from C++ as from assembly.  
  - Understand **abstraction layers** and how modern tools map back to low-level execution.  

- **Outcome**  
  - Gain **insight into hardware-level computation** and **low-level programming practices**.  
  - Build a foundation for future work in **systems, engine, and GPU programming**.

---

## ⚙️ Project Description

**NESlides** is a custom-built interactive slideshow for the **Nintendo Entertainment System**.  
- Move between slides using a character.  
- Destroy (shoot) every tile — even the text.  
- Each slide is stored as tilemap data on the cartridge.  
- The presentation is both *functional* and *destructible*.

To simplify content creation, we developed **[NESlidesEditor](https://github.com/JohnyTheCarrot/NESlidesEditor)** — a C++ desktop tool that allows easy slide design and NES ROM export.

---

## 🚀 Release

📦 **retro_console_and_emulator_programming-neslides-1.0.0-nes.zip**  
Contains the final NES ROM release of *NESlides*.  
Tested with **FCEUX** and **Mesen** emulators.

---

## 🧠 Final Thoughts

This project offered us a deep dive into **hardware-level programming** and **retro system architecture**, providing hands-on experience with memory management, CPU cycles, and the quirks of the **6502 processor**.  
It’s one of those projects that teaches you to *respect every byte*.

---

### ⚖️ License
This repository is licensed under the **MIT License** — feel free to explore, learn, or fork anything you find useful.
