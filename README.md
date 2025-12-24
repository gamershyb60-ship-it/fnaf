# fnaf
 # Five Nights at Freddy's - Fan Game

A browser-based recreation of the classic horror game Five Nights at Freddy's, built with React and Framer Motion.

## 🎮 Game Description

You are a night security guard at Freddy Fazbear's Pizza. Survive from 12 AM to 6 AM while managing limited power and avoiding animatronics that roam the building.

## ✨ Features

- **6 Challenging Nights** - Each night gets progressively harder
- **4 Animatronics** - Freddy, Bonnie, Chica, and Foxy, each with unique AI behaviors
- **Golden Freddy** - Rare easter egg encounter
- **Camera System** - Monitor 12 different locations
- **Power Management** - Strategic use of doors, lights, and cameras
- **Authentic Atmosphere** - Complete with sound effects, animations, and visual effects
- **Progressive Difficulty** - AI levels increase each night
- **Save System** - Continue from your highest unlocked night

## 🎯 How to Play

### Controls
- **Camera Button** - Open/close the security camera system
- **Door Buttons** - Close doors to block animatronics (costs power)
- **Light Buttons** - Check if animatronics are at your doors (costs power)

### Objective
Survive from 12 AM to 6 AM without getting jumpscared by the animatronics.

### Tips
- Monitor cameras to track animatronic movement
- Check Pirate Cove frequently - Foxy becomes more aggressive if ignored
- Close doors only when animatronics are nearby to conserve power
- If power runs out, Freddy will attack after a few seconds
- Listen for audio cues - footsteps mean an animatronic moved

## 🛠️ Technologies Used

- **React** - UI framework
- **Framer Motion** - Animations and transitions
- **Tailwind CSS** - Styling
- **Web Audio API** - Sound effects and music
- **Lucide React** - Icons
- **Base44 Platform** - Backend and hosting

## 📁 Project Structure

├── components/ │ └── game/ │ ├── MainMenu.jsx │ ├── Office.jsx │ ├── CameraView.jsx │ ├── AnimatronicModel.jsx │ ├── Jumpscare.jsx │ ├── NightComplete.jsx │ ├── PowerOutage.jsx │ ├── SoundManager.jsx │ └── AmbientSounds.jsx └── pages/ └── Game.jsx


## 🎮 Game Mechanics

### Animatronic AI
- **Freddy** - Moves through dining area, backstage, and east hall
- **Bonnie** - Takes the west hall route to your left door
- **Chica** - Uses kitchen and east hall to reach your right door
- **Foxy** - Hides in Pirate Cove, charges if not monitored

### Power System
- Base power drain: ~1% per minute
- Each door closed: +10% drain
- Each light on: +6% drain
- Cameras open: +8% drain

### Difficulty Scaling
- **Night 1**: Tutorial (easy)
- **Night 2-3**: Moderate challenge
- **Night 4-5**: Hard difficulty
- **Night 6**: Extreme challenge

## ⚠️ Disclaimer

This is a fan-made recreation for educational purposes. Five Nights at Freddy's is owned by Scott Cawthon and Steel Wool Studios.

## 📄 License

MIT License

---

**Good luck, and don't let them catch you! 🐻🐰🐔🦊**
