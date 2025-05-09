# Page Replacement Algorithm Simulator

Live Demo: https://page-replacement-simulator-one.vercel.app/

A browser-based **Page Replacement Algorithm Simulator** that empowers students to visualize and compare **FIFO**, **LRU**, and **Optimal** strategies step by step—complete with interactive controls, summary tables, and Chart.js–powered analytics—all without a backend server.

---

## 🚀 Introduction

This project brings to life three fundamental page replacement algorithms—**First-In-First-Out (FIFO)**, **Least Recently Used (LRU)**, and **Optimal**—to show how operating systems manage limited physical memory during page faults. Through a clean, web-based interface you can experiment with any reference string and frame count, helping bridge theoretical OS concepts with hands-on learning.

## 🔗 Live Demo

Try it now in your browser (no installation required!):  
https://page-replacement-simulator-one.vercel.app/

---

## ✨ Features

- **Algorithm Selection**: Instantly switch between FIFO, LRU, and Optimal.  
- **Custom Input**: Enter any comma-separated reference string and set the number of frames.  
- **Step-by-Step Navigation**: Watch each page access in real time, with clear hit vs. fault indication.  
- **Execution Table**: View a detailed log of frame contents per step, with new loads highlighted.  
- **Chart.js Analytics**: See an interactive pie chart of total hits vs. misses, updated on the fly.  
- **Light/Dark Mode**: Toggle themes; your preference is saved automatically.

---

## 🔧 Technologies

- **HTML5** and **CSS Grid** for responsive, mobile-friendly layout  
- **Vanilla JavaScript** for core simulation logic and DOM updates  
- **Chart.js** for seamless, animated pie charts  
- **localStorage** API for persisting user preferences  

---

## ⚙️ Installation

If you’d like to run the simulator locally:

1. Clone the repository  
   ```
   git clone https://github.com/Ayush-Gole8/PageReplacementSimulator.git
   cd PageReplacementSimulator
   ```
2. Open `index.html` in any modern browser—no server or build step required.

---

## ▶️ Usage

1. Open the landing page or the live demo link.  
2. Click the card for your desired algorithm (FIFO, LRU, or Optimal).  
3. Enter your reference string (e.g., `7,0,1,2,0,3,0,4`) and choose frame count.  
4. Hit **Simulate** to run the algorithm.  
5. Use **Prev** / **Next** to step through each access.  
6. Check out the pie chart summary of hits vs. misses.  
7. Toggle light/dark mode to suit your environment.

---

## 📚 Algorithms Explained

- **FIFO**: Evicts the oldest page in memory (queue behavior).  
- **LRU**: Removes the page that has not been used for the longest time (stack behavior).  
- **Optimal**: Looks ahead in the reference string to evict the page whose next use is farthest away.

---

## 🤝 Contributing

Your feedback and contributions are welcome!  
1. Fork the repo and create a new branch:  
   ```
   git checkout -b feature/YourFeature
   ```
2. Implement your changes and add any needed documentation.  
3. Commit your work:  
   ```
   git commit -m "Add AwesomeFeature"
   ```
4. Push to your fork:  
   ```
   git push origin feature/YourFeature
   ```
5. Open a Pull Request detailing your improvements.

---

## 👥 Contributors

- Ayush Gole  
- Nayan Pawar  
- Sheshank Singh

---

*Enjoy exploring page replacement algorithms!*