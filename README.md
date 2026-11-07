# 🌸 Bloom in AR – Interactive Flower Garden

## 🌷 Project Description

**Bloom in AR** is an Augmented Reality (AR) Flower Garden developed using A-Frame and AR.js.

The application creates a colourful virtual flower garden that appears when a user scans a Hiro marker using a mobile phone camera.

Users can explore a miniature garden containing colourful flowers, trees, butterflies, decorative objects and a garden pathway.

The project demonstrates 3D objects, animations, user interactions and marker-based augmented reality.

## ✨ Features

### 1. Hiro Marker Detection
- Uses the Hiro marker for augmented reality.
- Displays the virtual flower garden when the marker is detected.
- Includes a status banner that changes according to marker detection.

### 2. 3D Garden Environment
- Green grass and garden platform.
- Colourful decorative flowers.
- Trees and plants.
- Garden pathway.
- Decorative garden bench.
- Welcome sign.
- Garden lights.

### 3. Animations
- Flowers gently sway from side to side.
- A butterfly moves up and down continuously.

### 4. Interactive Elements

**Colour-Changing Ball**
- Users can tap the colourful ball.
- Its colour changes each time it is tapped.

**Interactive Sunflower**
- Users can tap the sunflower.
- The flower grows when tapped.
- Tapping it again returns it to its original size.

### 5. 3D Model
- Includes an external GLB butterfly model.
- Uses the glTF model format.
- The butterfly is animated using A-Frame animation.

### 6. Marker Status Banner

The application displays two different status messages:

- **Marker Found:** Displays a green banner when the Hiro marker is detected.
- **Marker Lost:** Displays a red banner when the Hiro marker is no longer visible.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- A-Frame 1.4.2
- AR.js 3.4.7
- glTF / GLB 3D Model

## 📁 Project Structure

```text
AR-Flower-Garden/
│
├── index.html
├── README.md
│
└── assets/
    └── butterfly.glb
```

## 🚀 How to Run the Project

### Step 1 – Download the Project

Download or clone the GitHub repository to your computer.

### Step 2 – Check the Assets Folder

Make sure the `butterfly.glb` file is available inside the `assets` folder.

### Step 3 – Open the Project

Open the project folder using Visual Studio Code.

### Step 4 – Run the Application

Install the Live Server extension in Visual Studio Code if it is not already installed.

Right-click `index.html` and select:

**Open with Live Server**

### Step 5 – Test the AR Application

1. Open the application using a supported HTTPS hosting service or a suitable local development setup.
2. Allow camera access.
3. Show the Hiro marker to the camera.
4. Explore the virtual flower garden.
5. Tap the interactive ball to change its colour.
6. Tap the sunflower to increase and decrease its size.

## 📱 Hosting

The application can be hosted using:

- Netlify Drop
- GitHub Pages

The application must be published over HTTPS to allow mobile camera access.

## 🎨 3D Model Credits

**Butterfly**

- Model Name: Butterfly
- Creator: Poly by Google
- Source: https://poly.pizza/m/eZBvUobx7mb
- Licence: Creative Commons Attribution 3.0 (CC BY 3.0)
- Licence URL: https://creativecommons.org/licenses/by/3.0/

The model is used as an external 3D asset in this project.

## 👥 Group Information

- Module: Augmented Reality
- Project Name: Bloom in AR – Interactive Flower Garden
- Assignment Type: AR activity
- Group Number: 50
- Group Members:

## 🌼 Conclusion

Bloom in AR demonstrates how Augmented Reality can transform a simple printed marker into an interactive virtual environment.

By combining 3D objects, animations and user interactions, the project provides an enjoyable virtual flower garden experience.