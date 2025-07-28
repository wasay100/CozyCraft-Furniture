# CozyCraft Furniture Website

A business website for CozyCraft Furniture with a functional contact form that sends emails to bsai24076@itu.edu.pk.

## Technologies Used
- HTML
- CSS (Tailwind CSS)
- JavaScript
- Express.js
- Node.js
- Nodemailer

## Setup Instructions

1. **Install Node.js dependencies:**
   ```
   npm install
   ```

2. **Configure Email Settings:**
   Open `server.js` and update the email configuration:
   - Replace `your-email@gmail.com` with your Gmail address
   - Replace `your-app-password` with your Gmail app password
   
   **To get Gmail App Password:**
   - Go to your Google Account settings
   - Enable 2-factor authentication
   - Generate an app password for this application

3. **Run the server:**
   ```
   npm start
   ```
   
   Or for development with auto-restart:
   ```
   npm run dev
   ```

4. **Access the website:**
   Open your browser and go to `http://localhost:3000`

## Features

- Responsive design using Tailwind CSS
- Product showcase with local PNG images
- Functional contact form that sends emails
- Smooth scrolling navigation
- Loading states and success/error messages

## Contact Form

When users fill out the contact form and click "Send Message", the form data is sent to the Express.js server, which then forwards the message via email to bsai24076@itu.edu.pk.

## File Structure

- `index.html` - Main website file
- `server.js` - Express.js server handling email functionality
- `package.json` - Node.js dependencies and scripts
- `*.png` - Product images
