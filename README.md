
# Thread Clone

![License](https://img.shields.io/badge/license-ISC-blue.svg)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)


## Overview

Thread Clone is a social media web application inspired by popular discussion forums. Built using Next.js, this application provides features for user authentication, real-time interactions, and media uploads. The project leverages Clerk for authentication, Mongoose for database interactions, and TailwindCSS for styling.

## Features

- **User Authentication**: Secure user sign-up and login using Clerk.
- **Discussion Threads**: Create, view, and participate in discussion threads.
- **Media Uploads**: Upload images and other media files using UploadThing.
- **Real-time Notifications**: Receive real-time updates and notifications.
- **Responsive Design**: Mobile-friendly, responsive UI built with TailwindCSS.

## Installation

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB instance running.

### Steps

1. **Clone the repository**
    ```bash
    git clone https://github.com/Aadityakesarwani/ThreadClone.git
    ```

2. **Set up the server**
    - Navigate to the root directory and install dependencies.
    ```bash
    npm install
    ```

    - Create a `.env` file in the root directory and add your environment variables.
    ```env
    MONGODB_URL=your_mongodb_url
    UPLOADTHING_SECRET=your_uploadthing_secret
    UPLOADTHING_APP_ID=your_uploadthing_app_id
    NEXT_CLERK_WEBHOOK_SECRET=your_clerk_webhook_secret
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
    CLERK_SECRET_KEY=your_clerk_secret_key
    ```

3. **Run the development server**
    - In the root directory, run the following command to start the development server.
    ```bash
    npm run dev
    ```

## Usage

- **Browse Threads**: Visit the homepage to browse the latest discussion threads.
- **Create Threads**: Sign up or log in to create new discussion threads.
- **View and Participate**: Click on a thread to view and participate in the discussion.
- **Upload Media**: Add images and other media files to your posts.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements, bug fixes, or feature additions.

1. **Fork the repository**
2. **Create your feature branch**
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. **Commit your changes**
    ```bash
    git commit -m 'Add some feature'
    ```
4. **Push to the branch**
    ```bash
    git push origin feature/your-feature-name
    ```
5. **Create a new Pull Request**

