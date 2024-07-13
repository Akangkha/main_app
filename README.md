# Furry Friends Alliance - Web Application
![image](https://github.com/user-attachments/assets/68111b9b-f580-4967-91b1-feeea8ff291a)

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)


## Project Description
Furry Friends Alliance is a non-profit organization dedicated to animal welfare. This innovative web application, built by our team, aims to foster community efforts in caring for street animals. The application is designed to help users place and manage bowls of food and water for street animals, ensuring continuous care and sustenance. Users can also track their pets and street animals they care for using QR tags generated by the website.

## Features
- **Bowl System**: Users can place bowls at specific locations, manually enter details or enable location services for automatic coordinates.
  ![image](https://github.com/user-attachments/assets/b6a98fac-5496-4b8e-9edf-eab2450d9036)

- **Dashboard with Google Maps API**: Spot different bowl locations in the area.
  ![image](https://github.com/user-attachments/assets/71914f84-6c77-4600-a108-c4c32d7eb4f1)
  
- **Dashboard with Pets and User details**: Keep track of pets details and user details.
  ![image](https://github.com/user-attachments/assets/6edbb729-c07f-4986-b9f7-2dfc7bfe0a6e)

- **Community Effort**: Users can view nearby bowls and take the initiative to refill them.
  ![image](https://github.com/user-attachments/assets/fdeed277-9b8d-4ca7-953d-878af2468152)

- **QR Tags**: Generate QR tags to track pets and street animals.
  ![image](https://github.com/user-attachments/assets/9d6a2856-c629-4aa2-85f4-479b189146c6)

- **Image Storage**: Uses Firestore to store images of bowls and animals.

## Technologies Used
- **Frontend**: React.js
- **Backend**: Node.js
- **Database**: MySQL
- **Image Storage**: Firestore
- **Hosting**: VPS with Nginx
- **Maps Integration**: Google Maps API

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Akangkha/furryfriendsalliance.git
   cd furry-friends-alliance
   ```

2. Install frontend dependencies:
   ```bash
   npm install
   ```

5. Set up Firestore and Google Maps API, and update the configuration file with the necessary API keys and credentials.

## Usage
 Start the development server:
   ```bash
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:3000` to access the application.

