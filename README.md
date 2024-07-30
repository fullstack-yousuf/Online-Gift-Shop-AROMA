# Online Gift Shop-AROMA

## Overview
A web-based application for managing an online gift shop.

## Features
- User registration and login
- Product catalog
- Shopping cart
- Order management
- Admin panel for managing products and orders
- Employee management

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/fullstack-yousuf/Online-Gift-Shop-AROMA.git
    ```
2. Set up the database:
    - Import the database schema from `database/db-carty.sql` into your MySQL server.
    - Use a tool like phpMyAdmin or a command line tool to execute the SQL file:
      ```bash
      mysql -u yourusername -p yourdatabase < database/db-carty.sql
      ```
3. Configure the project:W
    - Update database configurations in `AROMA_shop/config.php` with your database details.
    - Example configuration:
      ```php
      <?php
      return [
          'host' => 'localhost',
          'dbname' => 'yourdatabase',
          'user' => 'root',
          'password' => '',
      ];
      ```

## Usage
1. Start the server:
    ```bash
    php -S localhost:8000 -t public/
    ```
2. Access the application at `http://localhost:8000`.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Class Diagram
You can view the class diagram in the `docs/` directory.
