# TodoApp - PHP + Laravel + TailwindCSS

A simple and responsive Todo application built with PHP and Laravel, styled with TailwindCSS. This app allows users to create, manage, and track tasks efficiently.

## Features

- **Create Tasks**: Easily add new tasks.
- **Update Tasks**: Edit task details.
- **Delete Tasks**: Remove tasks when completed.
- **Mark Tasks as Completed**: Toggle task completion status.
- **Responsive UI**: Built with TailwindCSS for a sleek, responsive design.

## Tech Stack

- **Backend**: PHP, Laravel
- **Frontend**: TailwindCSS, Blade Templates
- **Database**: MySQL (or SQLite)

## Installation

### Requirements

- PHP 7.4 or higher
- Composer
- Laravel 8 or higher
- MySQL (or SQLite)

### Steps to Install

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/TodoApp.git
    cd TodoApp
    ```

2. Install dependencies:
    ```bash
    composer install
    ```

3. Set up the environment:
    - Copy `.env.example` to `.env`:
      ```bash
      cp .env.example .env
      ```
    - Update the database settings in the `.env` file.

4. Generate the application key:
    ```bash
    php artisan key:generate
    ```

5. Run the migrations:
    ```bash
    php artisan migrate
    ```

6. Start the development server:
    ```bash
    php artisan serve
    ```
    Your app will be available at `http://127.0.0.1:8000`.

## Usage

- Navigate to the home page to see the list of tasks.
- Add new tasks by clicking the "Add Task" button.
- Edit or delete tasks as needed.
- Mark tasks as completed by toggling the checkbox.

## Contributing

Feel free to open issues or create pull requests for improvements.

## License

This project is open-source and available under the [MIT License](LICENSE).
