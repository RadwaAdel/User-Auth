## User-Authentication
This project is a RESTful API for user authentication. 
## Setup
1. Clone the repository:
2. git clone <repository_url>
3.   Install the dependencies:
4. composer install
5.  Create a copy of the `.env.example` file and rename it to `.env`. Update the database credentials in the `.env` file.
6.   . Run the database migrations:  php artisan migrate
 ## Usage 
 1. Start the development server:  php artisan serve
 2. Make API requests to the following endpoints:  - Register a new user: `POST /api/auth/register` - Login: `POST /api/auth/login` - Get user profile: `GET /api/auth/profile` - Logout: `POST /api/auth/logout`  Please make sure to include the necessary request parameters and provide valid authentication tokens when required.  Feel free to explore the codebase and customize it according to your needs.
