Automated Email Sequencer
The Automated Email Sequencer is a MERN Stack web application designed to help users build and manage automated email sequences using a flowchart-based interface. It utilizes React Flow for visual representation, Agenda for scheduling emails, and Nodemailer for sending them.

Frontend
Technologies Utilized
React

React Flow

Axios

React Modal


Key Features
Visual Flowchart Interface: A user-friendly interface for designing email sequences.

Different Node Types:

Lead-Source: Specifies the recipient of the email sequence.

Cold-Email: Represents an email with subject and message content.

Wait/Delay: Introduces a delay between consecutive emails.

Interactive Forms: Simple modal-based forms for adding and modifying nodes.

Backend Connectivity: Sends node and edge data to the backend to initiate the email sequence process.

Setup Instructions
Configure the .env file: Set it up as per the .env.sample file.

Install necessary dependencies:

sh
Copy
Edit
cd Emailfrontend-main
npm install
Run the frontend server:

sh
Copy
Edit
npm run dev
Access the application: Open http://localhost:5173 in your web browser.

Backend
Technologies Utilized
Node.js

Express

Agenda

Nodemailer

MongoDB (via Mongoose)

Key Features
Automated Email Scheduling: Sends emails at predefined intervals based on the flowchart.

Email Delivery System: Uses Nodemailer to handle email sending efficiently.

Setup Instructions
Configure the .env file: Set it up as per the .env.sample file.

Install necessary dependencies:

sh
Copy
Edit
cd EmailBackend-main
npm install
Run the backend server:

sh
Copy
Edit
npm run dev
Once both frontend and backend are running, the Automated Email Sequencer will be fully functional and ready to use. 🚀









