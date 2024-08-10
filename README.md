# HomieSpace - Rental Gateway

HomieSpace is a comprehensive home rental booking system application built using NextJS, Supabase, Prisma, Kinde, ShadcnUI, and TailwindCSS. This application aims to streamline the process of booking rental homes by providing a user-friendly interface and robust backend.



### [Software Live Demo]()

## Table of Contents

1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)

## Features

- **User Authentication:** Secure user registration and login functionality with Kinde.
- **Search and Filter:** Effortlessly find rental homes using advanced search and filtering options.
- **Real-time Updates:** Receive instant updates on the booking process and availability.
- **Intuitive UI/UX:** User-friendly interface for a seamless browsing and booking experience.
- **Backend Services:** Leveraging the power of Supabase for database management, both images and tables.
- **Database Interaction:** Prisma ORM for efficient and scalable database interactions.
- **Geolocation Integration:** Display maps using geolocation data.
- **Wishlist Functionality:** Enable users to save and track their favorite properties.


## Technologies Used

- **NextJS:** A React framework for building server-side rendered applications.
- **Supabase:** An open-source alternative to Firebase providing a backend-as-a-service.
- **Prisma:** A database toolkit to query, migrate, and model your database.
- **Kinde:** An authentication tool for securing user registration and login processes.
- **ShadcnUI:** A library of reusable UI components for React.
- **TailwindCSS:** A utility-first CSS framework for rapidly building custom user interfaces.
  

## Installation

To install and run VISTA locally, follow these steps:

1. Clone the repository: `git clone https://github.com/Seew0/HomieSpace-Rental-Gateway`
2. Navigate to the project directory: `cd HomieSpace-Rental-Gateway`
3. Install the dependencies: `npm install`
4. Create a `.env` file based on the provided `.env.example`
5. Add all necessary credentials keys
6. Push the Prisma schema to reflect on the Supabase PostgreSQL Database with `npm run postinstall`
7. Upload your tables to Supabase `npm run migrate`
8. Run the application with `npm run dev`

After completing these steps, you should be able to run this project locally. If you encounter any issues or have any questions, please don't hesitate to reach out.

## Usage

After running the application, you can access it at `http://localhost:3000`. From there, you can register as a user, browse rental homes, make bookings, and much more.
