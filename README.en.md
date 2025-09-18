[Version Française](README.md)

# 🌿 Visual Garden Planner

**Bring your dream garden to life!** This web application allows you to design your vegetable patch or flower beds in a visual, simple, and intuitive way. As a pure front-end application (vanilla HTML, CSS, JavaScript), it runs directly in your browser with no installation or internet connection required. It's a single `html` file for maximum portability.

![Garden Planner Preview](URL_OF_YOUR_SCREENSHOT.png)
*(Remember to replace this line with a real screenshot of your project!)*

## 🚀 Live Demo

[**Launch the Garden Planner (Live Demo)**](https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/planificateur_jardin.html)
*(This link will work once the application is hosted, for example with GitHub Pages. See instructions at the end.)*

## ✨ Features

- **Background Image Loading**: Use a satellite map, a drone photo, or a land survey map as the base for your garden.
- **Accurate Scaling**: Set a scale by drawing a line over a known distance (e.g., a 10m wall). A visual measurement line guides you as you draw.
- **Customizable Plants**: Add your own plant types with a name, color, emoji, and recommended spacing.
- **Plant Actions**:
    - **Add**: Select a plant type and click on the plan to add it.
    - **Move**: Activate "Move" mode to drag and drop plants.
    - **Delete**: Activate "Delete" mode to remove a plant with a single click, or use right-click as a shortcut at any time.
- **Visual Representation**: Each plant is represented by a translucent circle corresponding to its size (diameter = spacing), with its emoji at the center.
- **Automatic Grid Placement**: Place dozens of perfectly aligned plants in a single click by defining a number of rows and columns.
- **Irrigation Planning**: Draw your drip irrigation system point by point, create branches, and get the total required pipe length in real-time.
- **Path Drawing**: Design the paths and walkways of your garden and get their total length.
- **Mulch Calculation**: Outline polygonal areas to calculate the required volume of mulch (in liters) based on the desired thickness.
- **Integrated Counters**: Keep an eye on the total number of plants and the count for each variety.
- **Local Save**: Save and load your entire plan (plants, irrigation, scale, etc.) directly in your browser via `localStorage`.
- **Image Export**: Export your final plan (background image + all drawn elements) as a PNG file.
- **Zero Dependency**: Built with pure HTML5, CSS, and JavaScript. No frameworks, no libraries, no build process. Lightweight, fast, and easy to modify.

## 🚀 How to Use It

It's incredibly simple:

1.  Download the `planificateur_jardin.html` file.
2.  Open it with any modern web browser (Firefox, Chrome, Edge, etc.).
3.  Start planning!

## 🏗️ Code Structure

The project is intentionally contained in a single file for maximum portability. The internal structure is as follows:

- **`<head>`**: Contains the `<style>` block with all the necessary CSS for the interface.
- **`<body>`**: Contains the HTML structure for the control panel (`#controls`) and the drawing area (`#canvas-container`).
- **`<script>`**: Contains all the JavaScript code that brings the application to life. The logic is commented to facilitate understanding and modifications.

## 💡 Ideas for Improvement

This project can still evolve! Here are a few ideas:

- [ ] Grid rotation for placement.
- [ ] A pre-configured library of plants (tomatoes, lettuces, etc.).
- [ ] An Undo/Redo function.
- [ ] Export and import the plan as a `.json` file for sharing.

Feel free to fork the project and suggest your own improvements!
