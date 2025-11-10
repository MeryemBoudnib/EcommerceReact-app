E-Commerce React App

Overview

This is a modern and responsive e-commerce website built with React and Vite.
The project features user authentication and authorization, search functionality, product details pages, shopping cart and checkout functionality, and a wishlist feature.

Features

User authentication and authorization

Search functionality for products

Product details page with images, descriptions, and reviews

Shopping cart and checkout functionality (Stripe integration ready)

Wishlist feature

Responsive design with mobile-friendly layout

Technologies

Frontend: React, Vite, Tailwind CSS, HTML5, CSS3
State Management: React Context API, Reducers, React Query
Routing: React Router
Forms & Validation: Formik, Yup
HTTP Requests: Axios
UI & Components: Flowbite, React Slick, FontAwesome

Folder Structure
src/          # Main application code
assets/       # Static assets (images, icons)
components/   # Reusable UI components
context/      # React Context for state management
pages/        # Application routes/pages
styles/       # CSS / Tailwind styles

Installation & Local Development

Clone the repository:

git clone https://github.com/MeryemBoudnib/EcommerceReact-app.git


Navigate to the project folder:

cd EcommerceReact-app


Install dependencies:

npm install
# or
yarn install


Start the development server:

npm run dev
# or
yarn dev


Open the application in your browser at http://localhost:5173

Usage

Browse products, add them to your cart or wishlist.

Test authentication by signing up or logging in.

Checkout process simulates a payment (can integrate Stripe)
