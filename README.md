# PathFinder

Overview

This project is a visual pathfinding tool that allows users to visualize various pathfinding algorithms in action. It provides an interactive interface where users can select different algorithms, set obstacles, and observe how the algorithms work to find the shortest path from a source to a destination on a grid.
Features

    Interactive Grid: Users can place obstacles on the grid, set source and destination points, and watch the selected algorithm navigate through the grid.
    Multiple Algorithms: Includes several popular pathfinding algorithms:
        A* Search
        Dijkstra's Algorithm
        Breadth-First Search (BFS)
        Depth-First Search (DFS)
        Greedy Best-First Search
    Responsive Design: The visualizer is designed to be responsive and can adapt to different screen sizes.

Technologies Used

    HTML/CSS: For the structure and styling of the web page.
    JavaScript (p5.js): Used for rendering the grid and implementing the pathfinding algorithms.
    Bootstrap: For responsive design and UI components like the navigation bar.
    Google Fonts: Raleway font is used for styling the text.

Getting Started
Prerequisites

To run this project, you'll need a modern web browser. No installation of any software is required.
Running the Visualizer

    Clone or Download the Repository:
        Clone the repository using Git or download the ZIP file.

    Open the index.html file:
        Simply open the index.html file in your browser.

    Using the Interface:
        Select an Algorithm: Use the dropdown menu to select the desired pathfinding algorithm.
        Set Source and Destination: Click on the grid to set the source and destination points.
        Add Obstacles: Click on the grid to place obstacles that the algorithm must navigate around.
        Visualize: Click the "Start" button to visualize the algorithm in action.
        Throw Obstacles: Automatically place random obstacles on the grid.
        Clear: Reset the grid to start over.

Project Structure

    index.html: The main HTML file that contains the structure of the page.
    sketch.js: Contains the JavaScript code for the visualizer, including the implementation of pathfinding algorithms and the grid management.
    Node Class: Implements a Node in the grid, with properties such as position, neighbors, and methods to show itself on the grid, handle clicks, and more.

Customization

You can customize the grid size, colors, and other properties by modifying the sketch.js file. For example, you can change the resolution variable to alter the size of each grid cell or adjust the colors used for different states (source, destination, obstacles, etc.).



https://github.com/user-attachments/assets/070283ef-5a0d-4787-828e-53fc095bd869

