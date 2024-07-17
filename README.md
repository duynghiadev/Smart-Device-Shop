# Creating the README.md file content

# Smart Device Shop

Welcome to the **Smart Device Shop** project! This repository contains the source code for my university graduation project, aimed at creating a comprehensive e-commerce platform for smart devices.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The Smart Device Shop is an e-commerce platform that provides a seamless shopping experience for users interested in purchasing smart devices. The platform features a user-friendly interface, a robust backend, and a secure payment system. This project was developed as part of my university graduation project, showcasing my skills in full-stack development.

## Features

- **User Authentication:** Secure login and registration system for users.
- **Product Catalog:** Browse and search a wide range of smart devices.
- **Product Details:** Detailed view of each product with images, descriptions, and specifications.
- **Shopping Cart:** Add, remove, and update items in the shopping cart.
- **Order Management:** Place orders and track their status.
- **Admin Dashboard:** Manage products, categories, and orders.
- **Responsive Design:** Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend:**

  - ReactJS
  - Redux
  - TailwindCSS
  - Axios

- **Backend:**

  - Node.js
  - Express.js
  - MongoDB
  - Mongoose

- **Authentication:**

  - JSON Web Tokens (JWT)
  - bcrypt.js

- **Payment:**
  - Stripe API

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/duynghiadev/Smart-Device-Shop.git
   cd Smart-Device-Shop
   ```

2. **Install dependencies for the client:**

   ```bash
   cd client
   npm install
   ```

3. **Install dependencies for the server:**
   ```bash
   cd ../server
   npm install
   ```

## Usage

1. **Start the client:**

   ```bash
   cd client
   npm start
   ```

2. **Start the server:**

   ```bash
   cd ../server
   npm start
   ```

3. **Open your browser and navigate to:**
   ```
   http://localhost:3000
   ```

## Screenshots

### Homepage

![Homepage](images/homepage-screenshot.png)

### Product Details

![Product Details](images/product-details-screenshot.png)

### Shopping Cart

![Shopping Cart](images/shopping-cart-screenshot.png)

### Admin Dashboard

![Admin Dashboard](images/admin-dashboard-screenshot.png)

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or inquiries, please contact me at [your-email@example.com](mailto:your-email@example.com).
"""

# Saving the content to README.md file

with open("/mnt/data/README.md", "w") as file:
file.write(readme_content)
