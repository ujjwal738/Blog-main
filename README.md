## Features

- **User Authentication**: Secure login and registration system powered by JWT (JSON Web Tokens) and bcrypt for password encryption.
- **Rich Text Editor**: A fully-featured editor supporting text formatting and media embedding.
- **Blog Management**: Effortless creation, editing, deletion, and sharing of blog posts.
- **Stripe Integration**: Integrated Stripe for payment processing (for testing purposes only).
- **Responsive Design**: Fully responsive UI built with Tailwind CSS for optimal viewing on all devices.
- **Search**: Advanced blog search functionality for quick content access.

## Frontend

- React.js
- Tailwind CSS
- React Router DOM
- React Icons
- React Hot Toast

## Backend

- Node.js
- Express.js
- MongoDB (via Mongoose)

## Additional Packages

- bcryptjs
- cors
- dotenv
- jsonwebtoken

## Setup Instructions

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/ujjwal738/react-vite-blog-platform.git
cd react-vite-blog-platform


node -v

cd frontend
npm install


cd ../backend
npm install

MONGO_URI=your_mongo_database_uri
JWT_SECRET=your_jwt_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
