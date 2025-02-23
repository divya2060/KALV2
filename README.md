# Co-Viewer PDF

This project implements a **Co-Viewer for PDF Slides** system, where multiple users can synchronize their current PDF page view. The admin user controls the current page, and the same page is automatically shown to all viewers in real-time. This project is designed for seamless user experiences in remote presentations, classrooms, or collaborative sessions.

## Features

- **Real-Time Synchronization**: When the admin changes the PDF page, all viewers' pages are synchronized automatically.
- **Multi-User Support**: Supports multiple viewers who can follow the admin's current PDF page in real-time.
- **Socket.IO for Communication**: Uses Socket.IO for real-time communication and data synchronization.
- **PDF Viewer**: A fully functional PDF viewer for displaying slides with support for page navigation.

## Tech Stack

- **Frontend**: ReactJS, HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **Real-Time Communication**: Socket.IO
- **PDF Rendering**: `react-pdf` for rendering PDF files on the frontend.

## Installation

### Prerequisites

Make sure you have the following installed:

- **Node.js** (>= 14.x.x)
- **npm** (>= 6.x.x)

### Steps to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/co-viewer-pdf-slides.git
   cd co-viewer-pdf-slides

2. Install dependencies for both the server and client:
    ```bash
    npm install
3. Install dependencies for the frontend:
    ```bash
    cd client
    npm install
4. Go back to the root directory and start the server:
    ```bash
    cd ..
    npm start
5. Open another terminal window, navigate to the client folder, and start the client:
    ```bash
    cd client
    npm start
6. The application should now be running at http://localhost:3000. You can test the viewer by opening multiple tabs or windows.

### Usage
- Admin User:

    - The admin can control the slide page by changing the page number.
    - All viewers will automatically be synchronized to the same page.

- Viewer Users:

    - Viewers will automatically follow the page changes made by the admin in real time.