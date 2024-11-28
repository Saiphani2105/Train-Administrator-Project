
https://github.com/user-attachments/assets/7fe4315f-62de-47aa-bf8c-192ad318cd86


---

# **Train Administrative System** 🚂🎟️  


### **Table of Contents**
1. [Introduction](#introduction)  
2. [Features](#features)  
3. [Technologies Used](#technologies-used)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Project Workflow](#project-workflow)  
7. [Future Scope](#future-scope)  
8. [License](#license)  
9. [Acknowledgments](#acknowledgments)  

---

## **Introduction**  
The **Train Administrative System** is a comprehensive platform designed to manage train bookings, cancellations, and schedules efficiently. With a user-friendly interface, it allows users to add trains, book tickets, view train schedules, and manage reservations seamlessly.

---

## **Features**  
- Add new trains with unique details like train number, name, and schedule.  
- Search trains by train number or name.  
- Book tickets with seat preferences.  
- View all booked tickets in a detailed chart.  
- Cancel tickets or remove entire train records.  
- Real-time updates to train and booking data.  

---

## **Technologies Used**  
- **Programming Language:** Python  
- **Libraries & Tools:**  
  - Pandas: For efficient data handling and manipulation.  
  - SQLite3: For managing a lightweight and reliable database.  
  - Streamlit: For creating an intuitive and interactive user interface.  

---

## **Installation**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Saiphani2105/Train-Administrative-Project.git
   cd Train-Administrative-Project
   ```  
2. Install the required Python packages:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Ensure SQLite3 is set up and accessible on your system.  

---

## **Usage**  
1. Run the application:  
   ```bash
   streamlit run main.py
   ```  
2. Navigate through the following functionalities via the Streamlit app:  
   - **Add Train:** Input train details to register a new train.  
   - **View Trains:** Display all available trains.  
   - **Search Train:** Look up trains by number or name.  
   - **Book Tickets:** Reserve seats based on user preferences.  
   - **View Tickets:** See all booked tickets in an organized chart.  
   - **Cancel Ticket:** Remove specific ticket entries.  
   - **Cancel Train:** Delete a train and its associated bookings.  

---

## **Project Workflow**  
1. **Train Management:**  
   - Admin users add, update, or delete train details.  

2. **Ticket Booking:**  
   - Users select trains and reserve seats with their preferences.  

3. **Reservation Handling:**  
   - All bookings are stored in an SQLite3 database for persistence.  

4. **Data Visualization:**  
   - Streamlit displays information such as train schedules and booking charts interactively.  

---

## **Future Scope**  
- Integration with real-time train schedules through APIs.  
- Implementation of user authentication for secure access.  
- Adding support for dynamic fare calculations.  
- Deployment as a web or mobile application.  

---

## **License**  
This project is licensed under the [MIT License](LICENSE).  

---

## **Acknowledgments**  
- **Pandas** for seamless data manipulation.  
- **SQLite3** for its lightweight database capabilities.  
- **Streamlit** for an effortless UI/UX experience.  

---

### **Contributions Welcome!**  
Feel free to fork this repository, make enhancements, and submit a pull request. Let’s build better systems together! 🚀  
