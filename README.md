# WebTechFinalProject
Samman Resorts Website for Web Techonologies Final Project

Samman Resorts is committed to offering excellent hospitality, aiming to illuminate the globe through tenderness and outstanding customer service. Inspired by a dedication to diversity, equality, and inclusion, we provide unforgettable experiences for every guest, ensuring that each stay is marked by comfort, elegance, and personal attention.

---

## **Project Overview**

The **Samman Resorts Booking System** is a web-based application that allows customers to manage their bookings and the Samman Team to oversee all bookings. The system employs a 3-tier architecture:  
1. **Presentation Tier** (Frontend): HTML, CSS, and JavaScript for user interface.  
2. **Logic Tier** (Backend): PHP for business logic.  
3. **Data Tier** (Database): MySQL for persistent data storage.

---

## **Key Features**

### **For Customers:**
- Browse through Samman Resorts' offerings of rooms and services.
- Make bookings for rooms and additional services.
- Manage personal bookings, including viewing, editing, and deleting them.

### **For Samman Team:**
- View and manage all bookings across all customers.
- Edit and delete bookings as necessary to maintain accurate records.

---

## **Technology Stack**
- **Frontend**: HTML, CSS, JavaScript  
  - Example Files: `Homepage.html`, `SammanStyle.css`  
- **Backend**: PHP  
  - Example Files: `Booking.php`  
- **Database**: MySQL  
  - Database Name: `webtech_fall2024_maisy_baer`

---

## **File Structure**

### **Uploaded Files**
- **Presentation Files**: Contains HTML and CSS files for building the user interface.  
- **Logic Files**: PHP files for processing business logic and handling requests.  
- **Database Files**: MySQL files for setting up the required database schema and seeding data.

---

## **Setup Instructions**

### **Requirements**
- Web Server: [XAMPP](https://www.apachefriends.org/) or similar (Apache, MySQL, PHP).
- Browser: Modern browser such as Chrome or Firefox.

### **Steps**
1. **Clone/Download the Project**:  
   Extract the provided `.zip` files (`assets.zip`, `db.zip`, `view.zip`) into your working directory.

2. **Configure the Database**:  
   - Import the MySQL database file (`webtech_fall2024_maisy_baer.sql`) into your local MySQL server.
   - Ensure the database name matches: `webtech_fall2024_maisy_baer`.

3. **Set Up the Backend**:
   - Place the PHP files in the `htdocs` folder of XAMPP or the appropriate directory of your web server.
   - Update database connection credentials in the PHP configuration file (`db_api.php').

4. **Run the Application**:
   - Start the web server and MySQL server.
   - Open your browser and navigate to `http://localhost/<project-folder>>`.

---

## **Usage Instructions**

1. **For Customers**:
   - Sign up and log in to the portal.
   - Browse available rooms and services.
   - Make bookings and manage them in the customer dashboard.

2. **For Samman Team**:
   - Log in with admin credentials.
   - View and manage all customer bookings.

---

## **Project Contributors**
This project is developed by Maisy Baer for the **CS 341 - Web Technologies** Fall 2024 course.

---

## **Future Enhancements**
- Adding payment gateway integration for online payments.
- Implementing advanced analytics for booking trends.
- Introducing customer feedback and reviews for continuous improvement.

---
