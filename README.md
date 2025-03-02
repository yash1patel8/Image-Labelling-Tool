# Pothole Detection Classification Tool 🕳️🚗

## Overview
The Pothole Detection Classification Tool is a powerful application designed to assist users in analyzing road conditions by uploading images and classifying various features such as potholes, cracks, lane markings, and more. This tool leverages advanced image analysis techniques to provide detailed insights into road quality, helping municipalities, road maintenance teams, and researchers maintain safer and more efficient roads.

The application is built using Streamlit, a modern Python library for creating interactive web applications, and integrates with Firebase for secure user authentication and robust data storage. The user-friendly interface ensures that users can easily navigate through the app and perform complex tasks with minimal effort.

## Key Features

### Image Upload & Analysis
- **Upload Images:** Easily upload multiple images of roads from your computer.
- **Image Preview:** View a preview of the uploaded images before classification.
- **Batch Processing:** Analyze multiple images in a single session.

### Road Condition Classification
- **Classification Options:** Classify roads into categories such as Good, Bad, or Unclear.
- **Custom Labels:** Add custom labels to classify specific road conditions.

### Feature Detection
- **Lane Markings:** Identify and classify lane markings.
- **Shadows:** Detect shadows that may affect road visibility.
- **Obstacles:** Identify obstacles such as debris, construction materials, or other hazards.
- **Cracks and Potholes:** Detect and classify different types of cracks and potholes.

### User Authentication
- **Secure Login:** Securely log in using your credentials.
- **Sign-Up:** Create a new account with a unique username and password.
- **Password Recovery:** Recover your password if you forget it.

### Project Management
- **Create Projects:** Start new projects to organize your road condition analysis.
- **Manage Projects:** Easily switch between existing projects.
- **Project Details:** View and edit project details, including project name and description.

### Data Storage
- **Firebase Integration:** Store classification results in a Firebase database.
- **Data Retrieval:** Retrieve and view stored classification data for further analysis.
- **Export Data:** Export classification results to CSV or JSON format for offline analysis.

### Interactive UI
- **User-Friendly Interface:** Intuitive design for easy navigation.
- **Visual Feedback:** Receive immediate visual feedback on your classifications.
- **Responsive Design:** Access the tool from any device with a web browser.

## How to Use

### Sign Up
1. **Navigate to the Home Page:** Open the application in your web browser.
2. **Click on "Sign Up":** Create a new account by providing your name, email, university name, username, and password.
3. **Submit:** Complete the sign-up process by clicking the "Sign Up" button.

### Login
1. **Navigate to the Home Page:** Open the application in your web browser.
2. **Click on "Login":** Enter your username and password.
3. **Submit:** Log in by clicking the "Login" button.

### Create/Select Project
1. **Navigate to the Project Selection Page:** After logging in, you will be redirected to the project selection page.
2. **Create a New Project:** Click on "New Project" and enter a project name.
3. **Select an Existing Project:** Choose an existing project from the dropdown menu.

### Upload Images
1. **Navigate to the Classify Images Page:** After selecting a project, you will be redirected to the classify images page.
2. **Upload Images:** Click on the "Choose images for classification" button and select multiple images from your computer.
3. **Select an Image:** Choose an image from the uploaded files to classify.

### Classify
1. **Analyze Road Conditions:** Use the provided options to classify the road condition and detect features.
2. **Submit Findings:** Click the "Submit" button to store your classification results in the database.

### View All Classifications
1. **Navigate to the View All Classifications Page:** Click on "View All Classifications" in the sidebar.
2. **View Classifications:** View all classifications for the selected project.
3. **Export Data:** Export the classification results to CSV or JSON format for further analysis.


