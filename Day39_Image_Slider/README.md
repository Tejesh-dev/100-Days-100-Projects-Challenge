# 🎡 Day 39: Image Slider / Carousel  

This project is part of my **#100Days100Projects challenge**, where I build a new project every day to improve my front-end and full-stack skills.  

On **Day 39**, I built an **Image Slider / Carousel** using **HTML, CSS, and JavaScript**.  
This component is widely used in real-world applications (e-commerce, portfolios, product showcases), so I wanted to understand how to create one from scratch instead of relying on libraries.  

---

## ✨ Features  
- ⏩ Auto-slide images every 3 seconds  
- ⬅️➡️ Next/Previous buttons for manual navigation  
- 🔘 Dot indicators to jump between slides (with active state)  
- 🎨 Smooth CSS transitions  
- 📱 Fully responsive layout  

---

## 🧠 Approach & Logic  


**JavaScript Logic**  
The **JavaScript code is the engine of the slider**, handling all the dynamic and interactive behavior.  

- **Element Selection**: The code selects all the necessary HTML elements, such as the slider container, navigation buttons, and dot indicators.  
- **Slider State**: It tracks the current image being displayed using a variable called `currentIndex`.  
- **Dynamic Movement**: The `updateSlider()` function uses CSS `transform` to shift the images horizontally, creating the sliding effect.  
- **Button and Dot Events**: Event listeners are added to the navigation buttons and dot indicators to change the `currentIndex` and update the slider in real time when clicked.  
- **Auto-Play Management**: A `setInterval()` function is used to automatically advance the slider every 3 seconds. User interaction (button clicks or dot clicks) resets this timer to prevent the auto-play from interrupting manual navigation.  

