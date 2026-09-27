# CineBook — Online Movie Ticket Booking System

A professional, frontend-only college project for an **Online Movie Ticket Booking System**, developed using **HTML5, CSS3 and JavaScript**.

## Project Overview

CineBook allows users to:
- Browse currently available movies
- Search movies
- View movie details
- Select city, theatre, date and show time
- Select cinema seats
- Calculate ticket price automatically
- Generate a digital booking ticket
- Print the ticket
- Run the complete project without a backend

This project is designed to be easy to understand, modify and deploy using **GitHub Pages**.

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Layout, responsive design and animations |
| JavaScript | Search, seat selection, booking logic and ticket generation |
| LocalStorage | Store demo booking data in the browser |
| GitHub Pages | Deployment |

## Features

### 1. Movie Listing
The home page displays movie cards with:
- Movie name
- Genre
- Duration
- Rating
- Ticket price
- Details button
- Book Now button

### 2. Movie Search
Users can search the movie list by movie name or genre.

### 3. Seat Selection
The booking page provides:
- Available seats
- Occupied seats
- Selected seats
- Automatic price calculation

### 4. Booking Summary
The summary updates whenever the user changes:
- City
- Theatre
- Date
- Show time
- Seats

### 5. Digital Ticket
After booking, a digital ticket is generated containing:
- Booking ID
- Movie
- Date
- Time
- Theatre
- City
- Selected seats
- Total price

### 6. Print Ticket
The ticket page includes a print button and print-friendly CSS.

## Folder Structure

```text
online-movie-ticket-booking/
│
├── index.html
├── movie-details.html
├── booking.html
├── ticket.html
│
├── css/
│   ├── style.css
│   └── responsive.css
│
├── js/
│   ├── main.js
│   ├── movies.js
│   ├── booking.js
│   └── ticket.js
│
├── images/
│   ├── posters/
│   ├── banners/
│   └── icons/
│
├── README.md
└── .gitignore
```

## How to Run Locally

### Method 1 — Direct
1. Download or clone the repository.
2. Open the project folder.
3. Double-click `index.html`.

### Method 2 — VS Code
1. Open the folder in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

## GitHub Deployment

### Step 1 — Create a repository

Create a new repository on GitHub, for example:

`online-movie-ticket-booking`

### Step 2 — Upload the project

Upload all files and folders while keeping the structure unchanged.

### Step 3 — Enable GitHub Pages

Open:

`Repository → Settings → Pages`

Under **Build and deployment**:
- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

Click **Save**.

After GitHub finishes deployment, the website will be available at:

`https://YOUR-USERNAME.github.io/online-movie-ticket-booking/`

Replace `YOUR-USERNAME` with your GitHub username.

## Git Command Method

```bash
git init
git add .
git commit -m "Initial commit - CineBook movie booking system"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/online-movie-ticket-booking.git
git push -u origin main
```

## Important Note

This is a frontend college project. It does **not** connect to a real cinema database, payment gateway or authentication server.

The booking is stored in the browser using `localStorage`.

## Future Scope

A full production version could add:
- User registration and login
- Node.js/Express backend
- MongoDB database
- Real theatre/movie APIs
- Real-time seat locking
- Online payment gateway
- Email/SMS ticket confirmation
- Admin dashboard
- Booking history
- QR-code verification
- Cloud deployment

## Academic Use

Suggested project title:

**ONLINE MOVIE TICKET BOOKING SYSTEM**

Suggested domain:

**Web Development / Internet & Web Technologies**

Suggested technologies:

**HTML, CSS, JavaScript**

## Author

Student Name: __________________________

Roll Number: ___________________________

Course: B.Tech / BCA / MCA

Department: Computer Science / IT

College: _______________________________

Academic Year: 2022–2026
