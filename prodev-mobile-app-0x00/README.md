# prodev-mobile-app-0x00

This project is part of the **ALX Mobile Development Setup** series. It demonstrates how to scaffold a React Native mobile application using the **Expo Router template**, test it with **Expo Go**, and document the initial setup process.

---

## **Project Objective**
- Set up your first mobile application using the **Expo Router template**.
- Modify the default home screen.
- Understand the project structure and reset process.

---

## **Steps Followed for Scaffolding**

1. **Navigate to the Parent Project Directory**  
   ```bash
   cd prodev-mobile-setup


Create the Project Folder

bash
Copy
Edit
mkdir prodev-mobile-app-0x00
cd prodev-mobile-app-0x00
Initialize the Expo Router App

bash
Copy
Edit
npx create-expo-app@latest .
Selected the default (TypeScript) Expo Router template.

Modify the Home Screen

Opened app/(tabs)/index.tsx.

Replaced:

tsx
Copy
Edit
<ThemedText type="title">Welcome!</ThemedText>
with:

tsx
Copy
Edit
<ThemedText type="title">** First App Created**</ThemedText>
Start the Development Server

bash
Copy
Edit
npx expo start
For Android: Scanned the QR code using Expo Go.

For iOS: Used the camera app to scan the QR code.

Reset the Project
Ran:

bash
Copy
Edit
npm run reset-project
Observations from reset-project Command
The reset-project command cleared caches and reset the Metro bundler environment.

The existing app folder was renamed to app-example.

A fresh app directory with default starter files was created.

Running the app after this command is like starting with a clean project.

Project Structure
app/(tabs)/index.tsx – Main entry screen (tab view).

components/ – Custom UI components like HelloWave and ThemedText.

assets/ – Images and other static assets.

tsconfig.json – TypeScript configuration for JSX and module paths.

Key Tools
Expo Go – To preview and test the app on your phone.

React Native – Cross-platform mobile development.

TypeScript – Strongly typed JavaScript.

Next Steps
Explore the default components (HelloWave, ParallaxScrollView) to understand how they work.

Push the project to GitHub:

bash
Copy
Edit
git add .
git commit -m "Initial Expo Router setup with ALX modifications"
git push origin main