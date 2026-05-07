# Quiz8
## Part 1: Imaging Technique Inspiration
The imaging technique I find inspiring is the after-image or motion trail effect seen in the anime Cyberpunk: Edgerunners, specifically used to represent the "Sandevistan" speed ability. I want to incorporate the multi-layered, color-shifted silhouettes that follow the main subject during fast movement. This technique is beneficial because it effectively communicates extreme speed and dynamic energy in a 2D space. It creates a visually striking "temporal echo" that aligns perfectly with the futuristic and high-action requirements of my upcoming project.
### Inspiration Images
![David Speed Effect 1](images/cyber1.png)
![David Speed Effect 2](images/cyber2.png)

## Part 2: Coding Technique Exploration
To implement this effect, I will utilize Arrays and Class Constructors in p5.js. By creating a class to manage individual "trail segments," I can store the character's previous X and Y coordinates in an array. The program will then iterate through this array to redraw the image at those past positions with decreasing transparency levels using the Image Transparency technique. This approach allows for efficient management of multiple trailing frames and provides precise control over the "fade-out" speed and color tinting.
### Coding Technique Example
**Screenshot of Technique:** ![Transparency Technique](images/astronaut.png)
**Example Implementation:** [p5.js Image Transparency Example](https://p5js.org/examples/imported-media-image-transparency/)
