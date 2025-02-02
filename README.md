# beyondChats - AI Chatbot

## Live Website

Check out the live deployment here:  
🔗 [BeyondChats](https://beyondchat-ten.vercel.app/)

## Features

- **User Authentication**: Secure registration, login, and Google OAuth support.
- **Email Verification**: Users must verify their email before accessing chatbot features.
- **Organization Setup**: Users enter their company details and auto-fetch metadata.
- **Website Scraping**: Scrape and analyze the company's website to train the chatbot.
- **AI Chatbot Training**: Automatic chatbot training based on scraped website data.
- **Chatbot Integration**: Users receive an embeddable script for chatbot deployment.
- **Test Chatbot**: Users can interact with the chatbot before deploying it.
- **Confetti UI for Success**: Beautiful animations when integration is successful.
- **Responsive Design**: Fully optimized for mobile and desktop using TailwindCSS.

---

## Prerequisites

Before running this project, ensure you have:

- **Node.js**: Installed on your system.
- **Git**: Version control to clone the repository.

---

## Steps to Clone and Run the Project Locally

### 1️ Clone the Repository

Use the following command to clone the repository:

```bash
git clone https://github.com/kazutokidigaya/beyondChats-frontend.git
```

Navigate into the project directory:

```bash
cd beyondChats-frontend
```

### 2 Install Dependencies

Run the following command to install all necessary packages:

```bash
npm install
```

### 3 Environment Variables

Create a .env file in the root directory and add the following:

```bash
VITE_FIREBASE_API_KEY=<Your Firebase API Key>
VITE_FIREBASE_AUTH_DOMAIN=<Your Firebase Auth Domain>
VITE_FIREBASE_PROJECT_ID=<Your Firebase Project ID>
VITE_FIREBASE_STORAGE_BUCKET=<Your Firebase Storage Bucket>
VITE_FIREBASE_MESSAGING_SENDER_ID=<Your Firebase Messaging Sender ID>
VITE_FIREBASE_APP_ID=<Your Firebase App ID>
```

### 4 Start the Development Server

To start the frontend on your local machine, run:

```bash
npm run dev
```

## 🔧 Technologies Used

React.js – Frontend framework.

Vite – Fast build tool.

TailwindCSS – For styling and responsiveness.

Firebase Authentication – Secure user authentication.

Axios – API requests handling.

React Router – Navigation and protected routes.

React Hot Toast – Notifications.
Canvas-Confetti – Success animations.
