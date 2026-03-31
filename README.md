# AI-GENERATED-3D-ASSET-PIPELINE
A web-based 3D asset pipeline where users input text or images to retrieve matching 3D models. The system maps keywords to predefined assets and displays them in an interactive viewer. It includes camera controls and generates short descriptions, demonstrating input interpretation, asset selection, and visualisation.

What it does
 * Accepts a text prompt 
 * Matches the input to a predefined 3D asset
 * Displays the model in an interactive viewer
 * Generates a short description of the selected object
 * Supports basic camera controls (rotate, zoom, reset)


How it works
The system uses a simple rule-based approach:
 * The input text is analysed using keyword matching
 * The closest matching asset is selected from a catalog
 * The corresponding .glb model is loaded into a 3D viewer

Tech used
 * HTML
 * CSS
 * JavaScript
 * model-viewer for 3D rendering

How to run
* Download or clone the repository
* Use the link
  

Limitations
 * Uses rule-based matching, not advanced AI
 * Some external 3D model links may fail or vary in scale
 * Uploaded images are not converted into 3D models


