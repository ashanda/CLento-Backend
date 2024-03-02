# API Service

This is a Laravel project that [briefly describe what your project does and its purpose].

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)

## Installation

To get this project up and running on your local machine, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/ashanda/CLento-Backend.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd CLento-Backend
    ```

3. **Install Composer dependencies**:

    ```bash
    composer install
    ```

4. **Copy the example environment file and configure it**:

    ```bash
    cp .env.example .env
    ```
    add .env custome variable API_VERSION=v1
   
6. **Generate the application key**:

    ```bash
    php artisan key:generate
    ```

7. **Run the database migrations**:

    ```bash
    php artisan migrate
    ```

8. **Generate passport key**:

    ```bash
    php artisan passport:keys
    ```
9. **Run Server**:
    
    ```bash
    php artisan serve
    ```
