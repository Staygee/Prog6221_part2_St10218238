RecipeApp is a simple console application for managing recipes. It allows users to enter, display, scale, and clear recipe data. The application also includes features to manage multiple recipes, calculate total calories, and notify the user when total calories exceed a specified threshold.

Features

1. **Enter a Recipe**: Allows users to enter the details of a new recipe, including ingredients, quantities, units, calories, food groups, and steps.
2. **Show All Recipes**: Displays a list of all entered recipes in alphabetical order.
3. **Display a Recipe**: Allows users to select and display a specific recipe from the list.
4. **Scale Recipe**: Allows users to scale the quantities of the ingredients by a specified factor.
5. **Clear All Data**: Clears all entered recipe data.
6. **Calorie Notification**: Notifies users when the total calories of a recipe exceed 300.


Usage

1. When the application starts, you will see a menu with options:
    Menu:
    1. Enter Recipe
    2. Show All Recipes
    3. Display a Recipe
    4. Scale Recipe
    5. Clear All Data
    6. Exit

2. Select an option by entering the corresponding number.

3. Follow the prompts to enter recipe details, display recipes, scale recipes, or clear data.

Example

Entering a Recipe

1. Select `1. Enter Recipe`.
2. Follow the prompts to enter the recipe name, number of ingredients, ingredient details (name, quantity, unit, calories, food group), and steps.

Displaying a Recipe

1. Select `3. Display a Recipe`.
2. Enter the name of the recipe you want to display.

Scaling a Recipe

1. Select `4. Scale Recipe`.
2. Enter the name of the recipe you want to scale.
3. Enter the scale factor (e.g., 2 to double the quantities).

Notifications

- The application will notify you if the total calories of a recipe exceed 300.

Code Structure

- `Ingredient` class: Represents an ingredient in a recipe.
- `RecipeStep` class: Represents a single step in a recipe.
- `Recipe` class: Manages a recipe including its ingredients and steps.
- `Program` class: Main class to manage user interaction and application flow.

Unit Testing

A unit test is provided to verify the total calorie calculation.


