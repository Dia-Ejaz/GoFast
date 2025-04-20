# GoFast
A smart carpooling web application designed exclusively for FAST University Lahore students. GoFast helps students connect for shared rides, reducing travel costs and promoting sustainability on campus.

---

## Overview
GoFast allows students to sign up using their university email and register as a **driver**, **passenger**, or **both**. The platform automatically matches users based on route proximity and timing, suggesting the shortest possible route using the **Google Maps API**.

---

## Features
- University email-based authentication  
- Role-based registration (Driver / Passenger / Both)  
- Smart ride matching using Google Maps API  
- Driver profile with vehicle details  
- User reviews and ratings  
- Admin dashboard for managing users and rides  

---

## Tech Stack
**Frontend**: HTML, CSS, JavaScript  
**Backend**: Python  
**Database**: Microsoft SQL Server (MSSQL)  
**APIs**: Google Maps API for route optimization

---

## Project Structure
```
GoFast/
├── frontend/        # HTML, CSS, JS files
├── backend/         # Python backend logic
├── database/        # MSSQL schemas and scripts
├── docs/            # Diagrams and documentation
└── README.md        # You're here!
```

---

## Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Dia-Ejaz/GoFast.git
   cd GoFast
   ```

2. **Set up the backend (Python)**  
   - Create a virtual environment  
   - Install required packages (`pip install -r requirements.txt`)  
   - Run the server (`python app.py` or similar entry point)

3. **Set up the database (MSSQL)**  
   - Execute SQL schema from `/database/schema.sql`  
   - Configure connection string in the backend

4. **Run the frontend**  
   - Open `index.html` in your browser  
   - Or serve via a local web server

---

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## License
MIT License
