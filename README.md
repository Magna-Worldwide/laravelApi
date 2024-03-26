# Laravel Web Application

This is a small web application built with Laravel that manages products and their categories.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
  - [Endpoints](#endpoints)
- [Video Demo](#video-demo)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)

## Installation

To run this application locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Magna-Worldwide/laravelApi.git
   cd laravelApi
   ```

2. **Install dependencies**:

   ```bash
   composer install
   ```

3. **Set up the environment**:

   - Copy the `.env.example` file to `.env`:

     ```bash
     cp .env.example .env
     ```

   - Update the database configuration in the `.env` file with your database credentials.

4. **Run migrations**:

   ```bash
   php artisan migrate
   ```

5. **Start the server**:

   ```bash
   php artisan serve
   ```

## Usage

### Endpoints

This web application provides the following API endpoints:

- **POST /api/products**: Create a new product.
- **PATCH /api/products/{id}**: Update a product.
- **DELETE /api/products/{id}**: Delete a product.
- **GET /api/products**: List all products.
- **POST /api/categories**: Create a new product category.
- **PATCH /api/categories/{id}**: Update a product category.
- **DELETE /api/categories/{id}**: Delete a product category.
- **GET /api/categories**: List all product categories.

Make HTTP requests to these endpoints using your preferred client (e.g., cURL, Postman, or any REST client) to interact with the application.

## Video Demo

To watch a demonstration of the application, you can download the video from the following link:

[Video Link on Google drive](https://drive.google.com/file/d/14Mbovco5Rx2qKjuQBPoDafQLwWLwse-z/view?usp=sharing)

Once downloaded, you can play the video using any video player on your local machine.


## Technologies Used

- Laravel
- MySQL

## Contributing

Contributions are welcome! If you find any bugs or want to add new features, feel free to open an issue or submit a pull request.

---