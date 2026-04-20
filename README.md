# Strobe Master Pro

Strobe Master Pro is a high-performance, browser-based single-page application (SPA) designed for visual effects, testing display refresh rates, and creating atmospheric lighting environments.

## ⚠️ Medical Warning
**PHOTOSENSITIVITY/EPILEPSY WARNING:** This application produces rapid light flickers. If you have a history of epilepsy or seizures, consult a medical professional before use. If you experience dizziness, altered vision, eye or muscle twitches, or loss of awareness, **immediately discontinue use.**

## 🚀 Features

- **Precision Frequency Control:** Adjust strobe rates from 1Hz up to 60Hz (limited by your monitor's refresh rate) with 0.1Hz increments.
- **Full Spectrum Color Choice:** Use the integrated color picker to strobe any hex code. Default is classic Black & White.
- **Auto-Cycle Mode:** A dynamic mode that oscillates the frequency between low and high ranges automatically using a smooth sine-wave loop.
- **Clean UI/UX:** Minimalist glassmorphism interface that can be hidden for a fully immersive experience.
- **Hardware Accelerated:** Uses `requestAnimationFrame` for the smoothest possible performance and timing accuracy.

## 🛠 How to Use

1. **Set your color:** Use the color picker to select your primary strobe color.
2. **Adjust Frequency:** Drag the slider to set your desired flashes per second (Hz).
3. **Auto Mode:** Toggle the "Auto-Cycle" switch to let the app automatically shift speeds.
4. **Go Fullscreen:** Click "Start Strobe" and press `F11` on your keyboard for a full-screen experience.
5. **Hide Controls:** Press the `H` key on your keyboard to hide the control panel.

## 🗺 Roadmap

- [ ] **Tap-to-Tempo:** Set strobe frequency by tapping to the beat of music.
- [ ] **Sound Reactivity:** Integration with Web Audio API to trigger flashes based on microphone input/bass frequencies.
- [ ] **Custom Patterns:** Ability to program sequences (e.g., SOS Morse code or heartbeat patterns).
- [ ] **Mobile Optimization:** Dedicated touch gestures for brightness and speed control.
- [ ] **Multi-Color Loop:** A mode that cycles through the rainbow while strobing.

## 🛠 Tech Stack

- **HTML5**
- **CSS3** (Flexbox, Backdrop-filters)
- **JavaScript** (ES6+, RequestAnimationFrame API)

## 📄 License
This project is open-source and available under the MIT License.
