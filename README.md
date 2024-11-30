# EduRAG: An AI-Powered Application for Personalized Learning

Welcome to EduRAG, an AI-powered education platform designed to provide personalized learning experiences for K-12 students using their course textbooks. This platform leverages Retrieval-Augmented Generation (RAG) to enhance the learning process.

## Table of Contents

- [EduRAG: An AI-Powered Application for Personalized Learning](#edurag-an-ai-powered-application-for-personalized-learning)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Features](#features)
  - [Tech Stack](#tech-stack)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Screenshots](#screenshots)
  - [Contributing](#contributing)
  - [Contact](#contact)

## Project Overview

EduRAG aims to facilitate personalized learning by integrating AI technologies with traditional educational content. The platform allows students to interact with their course materials more effectively, providing tailored learning experiences based on their needs.

## Features

- *Personalized Learning:* Tailored content recommendations based on student interaction.
- *User-Friendly Interface:* Easy-to-use frontend built with Streamlit.
- *Secure User Onboarding:* Authentication and data storage using Firebase.
- *Real-time Data Retrieval:* Efficient data handling with LangChain and Gemini Developer API.

## Tech Stack

- *Frontend:* Streamlit
- *Backend:* Firebase
- *Database:* ChromaDB
- *AI Integration:* LangChain, Gemini Developer API
- *Programming Languages:* Python

## Installation

Follow these steps to set up the project locally:

1. *Clone the Repository:*
   bash
   git clone https://github.com/Kira-1937/class.git
   cd EduRAG
   

2. *Set Up Virtual Environment:*
   bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   

3. *Install Dependencies:*
   bash
   pip install -r requirements.txt
   

4. *Configure Firebase:*
   - Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
   - Enable Email/Password Authentication.
   - Set up Firestore database.
   - Download the firebaseConfig object from the Firebase Console and update the firebase_config.json file in your project.

5. *Run the Application:*
   bash
   streamlit run app.py
   

## Usage

1. *Sign Up / Log In:*
   - Use the authentication interface to sign up or log in.
   
2. *Explore Courses:*
   - Browse through available courses and interact with personalized content.
   
3. *Real-time Learning:*
   - Experience real-time content retrieval and AI-driven recommendations.

## Screenshots

Caption("Screenshot01.jpeg"): Homepage of EduRAG.

Caption("Screenshot02.jpeg"): Select Your Class Subject & Chapter.

Caption("Screenshot03.jpeg"): Ask your Questions.

## Contributing

We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature-branch).
5. Create a new Pull Request.


## Contact

For any questions or inquiries, please contact:

- *Email:* vikram@ma.iitr.ac.in
