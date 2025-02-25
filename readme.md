# Dental Care Management System

A single-file Dental Care Management System built with HTML, CSS, and vanilla JavaScript, utilizing [TailwindCSS](https://tailwindcss.com/) and [DaisyUI](https://daisyui.com/) for a modern, dark-mode interface. This project is designed for dental clinics and provides role-based access with full CRUD operations for administrators, while offering a read-only view for doctors. In addition, this version includes static **Feedback** (with star ratings) and an **About Us** section.

## Features

- **Role-Based Login:**
  - **Admin:** Full access to manage Patients, Doctors, Appointments, Medicine Stock, Employees, and view Feedback and About Us.
  - **Doctor:** Read-only access to Patients and Appointments.
- **CRUD Operations (Admin Only):**
  - Create, Read, Update, and Delete records using modals powered by DaisyUI.
- **Additional Sections:**
  - **Feedback:** Displays static reviews with star ratings.
  - **About Us:** Provides static information about the system.
- **Dark Mode UI:**
  - A sleek, responsive dark theme with smooth transitions.
- **Data Persistence:**
  - All data is stored in the browser's `localStorage` to persist between sessions.

## Default Credentials

- **Admin:**  
  - **Username:** `admin`  
  - **Password:** `admin`
- **Doctor:**  
  - **Username:** `doctor`  
  - **Password:** `doctor`

## Getting Started

1. **Clone or Download:**  
   Download the single HTML file (e.g., `index.html`) from this repository.

2. **Dependencies:**  
   The project uses the following CDN links which are already included in the HTML file:
   ```html
   <link href="https://cdn.jsdelivr.net/npm/daisyui@4.12.23/dist/full.min.css" rel="stylesheet" type="text/css" />
   <script src="https://cdn.tailwindcss.com"></script>
