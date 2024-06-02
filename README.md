# Chirper App Readme

---

## Introduction

Chirper allows users to post text-format updates called "chirps", view chirps from other users, follow/unfollow other users, and receive notifications when followed users create new chirps.

## Features

-   **Chirp Creation:** Users can create text-format posts called "chirps".
-   **Chirp Management:** Users can update and delete their own chirps.
-   **Timeline:** The home page displays chirps from all users.
-   **Follow/Unfollow:** Users can follow/unfollow other users to customize their timeline.
-   **Notifications:** Users receive notifications when followed users create new chirps.
-   **User Authentication:** Secure user authentication system allows users to sign up and log in.
-   **CRUD Operations:** Implements Create, Read, Update, and Delete operations for chirps.
-   **Data Validation:** Input data is validated to ensure integrity and prevent errors.
-   **Database Interaction:** Efficiently interacts with a database to store and retrieve chirps and user information.
-   **Middleware:** Middleware is used for authentication, ensuring only authenticated users can access certain features.
-   **Routing:** Utilizes Laravel's routing system to define application endpoints and handle requests.
-   **Rendering views with Inertia:** Renders vue pages using Inertia for a clean separation of logic and presentation.
-   **Forms and CSRF Protection:** Forms are implemented securely with Laravel's built-in CSRF protection mechanism.

## Installation

1. Clone the repository: `git clone <repository_url>`
2. Navigate to the project directory: `cd chirper`
3. Run `composer install` to install dependencies.
4. Set up your environment variables in the `.env` file.
5. Run `php artisan migrate` to migrate the database schema.
6. Serve the application: `php artisan serve`

## Usage

1. Visit the application URL in your web browser.
2. Sign up or log in to start using Chirper.
3. Create, view, update, or delete chirps.
4. Follow other users to customize your timeline.
5. Receive notifications when followed users create new chirps.
