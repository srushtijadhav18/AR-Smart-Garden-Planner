# AR Smart Garden Planner 🌱

An augmented reality (AR) mobile application built with Unity that allows users to visualize plants in real-world environments, explore preset plant models, and receive plant recommendations based on their preferences.

## 📌 Project Overview

AR Smart Garden Planner combines Augmented Reality and preference-based plant recommendations to make garden planning more interactive and accessible. Users can explore different plants, visualize them in their surroundings, and experiment with virtual garden arrangements before making physical changes.

## ✨ Features

### 1. Augmented Reality Plant Placement
- Detects suitable real-world surfaces using AR plane detection.
- Allows users to place virtual plants in their surroundings.
- Supports placing multiple plants in an AR environment.

### 2. Preset Plant Collection
- Provides a collection of realistic plant models.
- Allows users to select different plants and experiment with garden layouts.

### 3. Smart Plant Recommendations
- Allows users to specify preferences based on:
  - Light requirements
  - Available space
  - Maintenance level
- Highlights a plant that best matches the selected preferences.

### 4. Plant Interaction and Customization
- Supports repositioning placed plants through touch interaction.
- Supports resizing plants using a two-finger pinch gesture.
- Allows users to clear placed objects and start a new arrangement.

### 5. Interactive Garden Planning
- Combines plant selection, recommendations, and AR visualization in one mobile application.
- Helps users explore different plant combinations and garden layouts.

## 🛠️ Technologies Used

- **Unity** — Application development and 3D scene management
- **C#** — Application logic and interaction scripts
- **AR Foundation** — Cross-platform augmented reality functionality
- **ARCore** — Android AR support
- **TextMesh Pro** — UI text rendering
- **Unity UI** — Interface components and user interaction

## ⚙️ Development Changes

The project was updated to improve plant placement and interaction:

- Removed automatic plant placement at application startup.
- Added validation for plant, L-system, and garden selections.
- Restricted placement to detected AR planes.
- Added touch-based selection and repositioning logic for placed plants.
- Added pinch-to-resize interaction.
- Added collider support for selecting placed plants when required.
- Improved handling of UI interactions to reduce accidental placement.
- Updated incompatible plant materials to use a compatible Universal Render Pipeline shader where needed.

## 📱 Requirements

- Unity Editor compatible with the project configuration
- Android device supporting ARCore
- AR Foundation and ARCore XR Plugin
- Camera permission enabled
- A well-lit environment with surfaces suitable for AR plane detection

## 🚀 How to Run

1. Clone or download this repository.
2. Open the project using the compatible Unity Editor version.
3. Allow Unity to import the project assets and packages.
4. Open the main AR scene.
5. Verify the AR Session, AR Camera, AR raycast, plane detection, and plant prefab references.
6. Switch the build platform to Android.
7. Verify the ARCore settings in XR Plug-in Management.
8. Connect an ARCore-compatible Android device and build and run the application, or build an APK for installation.

## 🎮 How to Use

1. Launch the application and grant camera permission.
2. Move the device to scan the surrounding environment.
3. Wait for the application to detect a suitable surface.
4. Select a plant from the available options.
5. Tap a detected surface to place the plant.
6. Use the available plant preferences to view the recommended plant.
7. Experiment with plant placement and resizing.
8. Clear the arrangement when you want to start again.

## 🔮 Future Improvements

- Expand the plant database with more varieties.
- Improve plant selection and drag interaction.
- Add richer garden layouts and customization options.
- Incorporate additional plant suitability factors.
- Improve recommendation logic and provide explanations for recommended plants.
- Optimize rendering and performance across Android devices.

## 🎓 Project Purpose

This project demonstrates how augmented reality and preference-based recommendations can be combined to support interactive garden planning. It provides a foundation for visualizing plant arrangements in real-world spaces before implementing them physically.



Add the applicable license here. If this project is based on an existing repository, review its original license and attribution requirements before choosing a license for your modified version.
