# Automated Email Sequencer

The **Automated Email Sequencer** is a MERN Stack web application designed to help users build and manage automated email sequences using a flowchart-based interface. It utilizes **React Flow** for visual representation, **Agenda** for scheduling emails, and **Nodemailer** for sending them.

---

## Technologies Utilized

### Frontend
- **React**
- **React Flow**
- **Axios**
- **React Modal**

### Backend
- **Node.js**
- **Express**
- **Agenda**
- **Nodemailer**
- **MongoDB (via Mongoose)**

---

## Key Features

### Frontend
- **Visual Flowchart Interface**: A user-friendly interface for designing email sequences.
- **Different Node Types**:
  - **Lead-Source**: Specifies the recipient of the email sequence.
  - **Cold-Email**: Represents an email with subject and message content.
  - **Wait/Delay**: Introduces a delay between consecutive emails.
- **Interactive Forms**: Simple modal-based forms for adding and modifying nodes.
- **Backend Connectivity**: Sends node and edge data to the backend to initiate the email sequence process.

### Backend
- **Automated Email Scheduling**: Sends emails at predefined intervals based on the flowchart.
- **Email Delivery System**: Uses Nodemailer to handle email sending efficiently.

---

## Setup Instructions

### Frontend Setup

1. **Configure the .env file**:  
   Set up the `.env` file as per the provided `.env.sample` file.

2. **Install necessary dependencies**:

    ```bash
    cd Emailfrontend-main
    npm install
    ```

3. **Run the frontend server**:

    ```bash
    npm run dev
    ```

4. **Access the application**:  
   Open [http://localhost:5173](http://localhost:5173) in your web browser.

---

### Backend Setup

1. **Configure the .env file**:  
   Set up the `.env` file as per the provided `.env.sample` file.

2. **Install necessary dependencies**:

    ```bash
    cd EmailBackend-main
    npm install
    ```

3. **Run the backend server**:

    ```bash
    npm run dev
    ```

---

## Final Notes

Once both the frontend and backend are running, the **Automated Email Sequencer** will be fully functional and ready to use. 🚀
