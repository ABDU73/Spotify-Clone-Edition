# **Spotify App**

_A Spotify-like web application that allows users to sign up, log in, manage their profiles, and interact with media content. Built using React with typeScript for the frontend, Node.js for the backend, and integrated with Cloudinary for media storage and Clerk for user authentication._


## Features

1. **Backend `.env` Variables**: Instructions on setting up environment variables for the backend, including MongoDB URI, Cloudinary keys, and Clerk authentication keys.
   
2. **Frontend `.env` Variables**: How to configure the frontend `.env` with the Clerk public key.

3. **Installation Instructions**: Step-by-step instructions on how to set up both the frontend and backend of the application, including installing dependencies and starting the servers.

4. **Usage**: Describes how to interact with the app after it's set up.

5. **Deployment**: Tips on how to deploy the application securely while ensuring environment variables are handled properly.

6. **Technologies**: A list of technologies used in the project, such as React, Node.js, MongoDB, and Cloudinary.




## Project Setup

Before starting the project, you need to configure environment variables for both the backend and frontend.


### Backend Environment Variables

In the **backend** folder, create a `.env` file and set the following variables:

```bash
PORT=5000                  # The port on which the backend server will run
MONGODB_URI=your-mongo-db-uri    # Connection string for your MongoDB database
ADMIN_EMAIL=your-email@example.com   # Admin email used for app management
NODE_ENV=development        # Environment mode (e.g., development, production, test)

# Cloudinary integration for media storage
CLOUDINARY_API_KEY=your-cloudinary-api-key
CLOUDINARY_API_SECRET=your-cloudinary-api-secret
CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name

# Clerk authentication keys
CLERK_PUBLISHABLE_KEY=your-clerk-publishable-key
CLERK_SECRET_KEY=your-clerk-secret-key
