# Job Portal

Job Portal is a web application built using the popular PHP framework Laravel and designed with the CSS framework Tailwind. It serves as a platform applying for jobs, and also advertising jobs.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Features](#features)

  
## Getting Started

These instructions will help you get a copy of the project up and running on your local machine or web server.

### Prerequisites

- [PHP](https://www.php.net/) >= 7.4
- [Composer](https://getcomposer.org/)
- [Laravel](https://laravel.com/)
- [Tailwind](https://tailwindcss.com/)

### Installation

Clone the repository:

   ```bash
   git clone [https://github.com/your-username/your-repo](https://github.com/Olami2596/LARAVEL-TAILWIND-TASK-MANAGER).git
   ```

Navigate to the project directory:

   ```bash
   cd your-repo
   ```

Install dependencies:

   ```bash
   composer install
   npm install
    # or
   yarn install
   ```

Set up your environment variables:

   ```bash
    cp .env.example .env
    # configure database and other necessary settings in .env
    php artisan key:generate
   ```

Run migrations and seed the database:

   ```bash
    php artisan migrate --seed
   ```

Start the development server:

   ```bash
    php artisan serve
   ```



### Features

1. **Job Creation:**
   
   Easily create and delete jobs, add the job requirements, salary and details.

2. **Job Application:**
   
   Easily apply for jobs. A page containing jobs that has been applied for by user. 

3. **Authentication:**

   Users can login to apply for jobs, companies and recruiters can also create accounts to create jobs on the site.


