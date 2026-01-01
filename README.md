# 🚀 Big-O Complexity Visualizer

A dynamic, interactive React application designed to help developers visualize the growth of different time complexities. Instead of looking at static charts, users can "race" different algorithms to see how drastically execution time changes as input size () grows.

## 💡 The Problem
Big-O notation is often taught as abstract math. Beginners frequently underestimate the massive gap between  and , or why  is considered "disastrous." This tool makes that gap visible through real-time animation.

## ✨ Features

* **Interactive Input ():** Use a slider to adjust the input size and watch the complexity curves react.
* **The Complexity Race:** Animate "balls" representing different complexities ( to ) to see which ones finish instantly and which ones fly off the charts.
* **Dynamic Scaling:** A smart coordinate system that scales the graph visually so you can compare  and  on the same screen.
* **Real-time Stats:** Live calculation of operations based on the current .
* **Color-Coded Feedback:** Green for efficient, Yellow for acceptable, and Red for "Danger Zone" complexities.

## 🛠️ Tech Stack

* **React:** For the UI and state management.
* **Framer Motion:** Powering the "racing" animations and smooth transitions.
* **SVG (Scalable Vector Graphics):** Used for rendering the mathematical curves and coordinate system.
* **Lucide React:** For clean, minimalist iconography.
* **Tailwind CSS:** For sleek, modern styling.

## 📈 Complexities Visualized

| Complexity | Name | Efficiency |
| --- | --- | --- |
| O(1) | Constant | Excellent |
| O(log n) | Logarithmic | Excellent |
| O(n) | Linear | Good |
| O(n log n) | Linearithmic | Decent |
| O(n^2) | Quadratic | Poor |
| O(2^n) | Exponential | Terrible |
| O(n!) | Factorial | Nightmare |

## 🚀 Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/Faizal661/complexity-visualizer.git

```


2. **Install dependencies**
```bash
npm install

```


3. **Run the development server**
```bash
npm run dev

```



## 🧠 Lessons Learned

* **Handling Large Numbers:** Implementing logic to prevent browser crashes when calculating  for large inputs.
* **Coordinate Mapping:** Learning how to map abstract mathematical functions to an SVG pixel-grid coordinate system .
* **Animation Synchronization:** Using Framer Motion's `animate` prop to link physics-based movement to React state.

---

##### Mohammed Faizal T
