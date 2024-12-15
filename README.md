# Store It - Documentation

![Alt text](./public/assets/images/Add%20a%20heading.png "Optional Title")

## Overview

Store It is a storage management and file-sharing platform that allows users to effortlessly upload, organize, and share files. Built with cutting-edge technology, it provides a seamless experience for managing your data, whether for personal or professional use.

This application leverages **Next.js 15**, **TypeScript**, **TailwindCSS**, and the **Appwrite Node SDK**, combined with modern design principles for a responsive and user-friendly experience.

---

## Tech Stack

- **React 19**
- **Next.js 15**
- **Appwrite**
- **TailwindCSS**
- **ShadCN**
- **TypeScript**

---

## Features

### Authentication

- **Appwrite-Powered**: Seamless signup, login, and logout functionality with OTP support.

### File Management

- **File Uploads**: Upload a variety of file types (documents, images, videos, audio).
- **File Viewing**: Browse and view uploaded files directly.
- **Rename/Delete Files**: Manage files effortlessly with rename and delete options.
- **File Sharing**: Share uploaded files with others for collaboration.
- **File Downloads**: Download any uploaded file with ease.

### Dashboard

- **Dynamic Insights**: View total and consumed storage, recent uploads, and file summaries grouped by type.

### Search and Sorting

- **Global Search**: Quickly find files or shared content with a robust search.
- **Sorting Options**: Organize files by date, name, or size.

### Design and Responsiveness

- **Modern Minimalist UI**: A sleek design that adapts to all devices.

---

## Getting Started

### Prerequisites

- **Node.js**: Ensure Node.js (v16+) is installed on your system.
- **Appwrite Setup**: Configure your Appwrite instance with necessary databases and storage.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/aymansdk/vaultify
   cd vaultify
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure environment variables:
   Create a `.env.local` file and add the following:

   ```env
   NEXT_PUBLIC_APPWRITE_ENDPOINT=<Your Appwrite Endpoint>
   NEXT_PUBLIC_APPWRITE_PROJECT=<Your Appwrite Project ID>
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```
5. Access the app at `http://localhost:3000`.

---

## Deployment

To deploy Store It, use platforms like **Vercel** or **Netlify**. Ensure that environment variables are set appropriately in the deployment dashboard.

---

## API Endpoints

### Authentication

- **Signup/Login**: Handled by Appwrite's Authentication APIs.

  ![Alt text](./public/assets/images/Flowchart%20-%20Frame%201.jpg "Optional Title")

### File Operations

- **Upload File**: Utilizes Appwrite's storage functionality.
- **Rename/Delete File**: Modify file details or remove files.
- **Share File**: Generate shareable links.
- **Download File**: Enable file download from storage.

---

## Contribution Guidelines

We welcome contributions! Follow these steps:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push and create a pull request:
   ```bash
   git push origin feature/your-feature-name
   ```
