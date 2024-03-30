# SymRecipe---Streamlined-Recipe-and-Ingredient-Management-System-with-Symfony-6
SymRecipe is a Symfony app for managing recipes. It offers CRUD operations, admin dashboard, user authentication, and more.

## Features

- CRUD operations for recipes
- Detailed recipe information (ratings, images, creation date, etc.)
- Admin dashboard for managing recipes and ingredients
- Public and private recipe listings
- Contact support via email
- Security features (role-based authentication, user authentication)
- Custom command creation
- Twig filters for enhanced user interface
- WebPack Encore for efficient asset management
- Caching for improved performance
- Event listeners and event subscribers for error handling and other functionalities

## Installation

To install SymRecipe, follow these steps:

1. Clone the repository:
git clone https://github.com/your_username/symrecipe.git


2. Navigate to the project directory:
cd symrecipe


3. Install dependencies:
composer install


4. Set up the database:
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate


5. Install front-end dependencies:
yarn install


6. Build front-end assets:
yarn encore production


7. Run the Symfony development server:
symfony server:start


8. Access the application in your web browser:
http://localhost:8000


## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues for any enhancements or bug fixes.


##Author : Nabil Lambattan
