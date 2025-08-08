# Interactive Family Tree Visualizer

A responsive family tree built with **HTML**, **CSS**, **JavaScript** and **D3.js**.  
It dynamically renders relationships from a JSON dataset, supports spouse and child connectors and highlights the full lineage on hover.

![Preview Screenshot](./preview.png) <!-- Replace with an actual screenshot if available -->

---

## Features

- **Dynamic Data-Driven Layout** – Renders family tree structure directly from a JSON dataset.
- **Spouse & Child Connections** – Handles multiple relationships with clean connector lines.
- **Multiple Roots** - Seamlessly handles multiple root nodes without breaking the flow.
- **Hover Highlights** – Hover over any person to highlight their complete lineage.
- **Zoom & Pan** – Navigate large trees with ease.
- **Responsive Design** – Scales to different screen sizes.
- **Lightweight & Fast** – Pure HTML/CSS/JS with no heavy build steps.

---

## Project Structure
```bash
.
├── index.html # Main HTML file
├── style.css # Styles for nodes, lines, and layout
├── script-forest.js # Main JavaScript logic (D3.js rendering)
├── people.json # Family data source
├── Photos/ # Optional profile images
└── README.md # Project documentation
```

---

## Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/YOUR-USERNAME/family-tree.git
cd family-tree
```

### 2. Customize the Dataset
- Modify the data in the ```people.json``` file to suit your needs.
- Add any relevant images to ```./Photos``` and ensure the right path is being used in the json file.

### 3. Open in your Browser
- Open the ```index.html``` file in your preferred browser to view the Family Tree. Requires the use of Live server in VS Code or a HTTP server for JSON fetch to work.
---

## Live Demo
Once deployed via GitHub Pages, your project will be available here:
https://YOUR-USERNAME.github.io/family-tree

---

## Built With
- D3.js
- HTML5, CSS3, JavaScript.