# Flavour Fusion - Recipe App

## Overview
Flavour Fusion is a web-based recipe application that allows users to search for and explore different recipes using the **MealDB API**. The app fetches recipes based on user queries and displays relevant details such as ingredients, instructions, and images. This interactive application provides an easy way to discover and try new dishes from different cuisines.

## Features
- **Search Functionality**: Users can search for recipes by name, making it easy to find specific dishes.
- **Dynamic Recipe Display**: Recipes are fetched from an API and displayed dynamically in an easy-to-read grid layout.
- **Recipe Details Popup**: Users can view ingredients and cooking instructions in a popup modal, enhancing usability.
- **Interactive UI**: Visually appealing design with smooth transitions and hover effects for better engagement.
- **Responsive Design**: Works well on various screen sizes, including mobile devices and tablets, ensuring accessibility for all users.
- **API Integration**: Fetches real-time data from the **MealDB API**, providing an extensive collection of recipes.

## Technologies Used
- **HTML** - Structuring the web application with semantic elements.
- **CSS** - Styling the layout with modern design principles, including flexbox and grid.
- **JavaScript** - Handling API calls, user interactions, and dynamic content updates.
- **MealDB API** - Provides extensive recipe data, including ingredients and instructions.

## Installation & Setup
### Prerequisites
Ensure you have the following installed on your system:
- A modern web browser (Chrome, Firefox, Edge, etc.)
- A text editor (VS Code, Sublime Text, or Notepad++)
- Internet connection for fetching data from the API

### Steps
1. Download or clone the repository from GitHub.
2. Extract the files if downloaded as a ZIP.
3. Open the `index.html` file in your web browser.
4. Start searching for recipes and exploring new dishes!

## File Structure
```
📂 Flavour-Fusion
│-- index.html       # Main HTML structure of the application
│-- style.css        # Styling and layout of the app
│-- script.js        # JavaScript file handling logic and API calls
```

## Usage
1. Open the app in a web browser.
2. Enter a recipe name in the search box and click **Search**.
3. View a list of recipes matching your query, each displaying an image, name, and category.
4. Click **View Recipe** on any recipe to see detailed ingredients and cooking instructions.
5. Scroll through the popup window to read full instructions and ingredient lists.
6. Close the details popup by clicking the close button or pressing the Escape key.
7. Explore more recipes by entering different queries in the search bar.

## API Integration
- The app uses the **MealDB API** to fetch recipes dynamically.
- API Endpoint: `https://www.themealdb.com/api/json/v1/1/search.php?s={query}`
- Each API request retrieves meal details, including:
  - Meal name
  - Category and region
  - Image thumbnail
  - Ingredients with measurements
  - Step-by-step cooking instructions
- JavaScript fetch requests handle the API calls and process JSON responses to dynamically display content.

## Responsive Design
- **Desktop View**: Grid-based layout for displaying multiple recipes efficiently.
- **Tablet & Mobile View**: Adjusted grid layout and font sizes for better readability and accessibility.
- **Smooth Navigation**: CSS media queries ensure a seamless user experience across different screen sizes.

## Future Enhancements
- **Add Favorite Recipes**: Allow users to save and revisit their favorite recipes.
- **Filter by Category & Region**: Enable filtering recipes based on cuisine type for better user experience.
- **Dark Mode**: Introduce a dark mode toggle for improved visual comfort.
- **User Authentication**: Implement user accounts to save preferences and history.
- **Ingredient-Based Search**: Allow users to find recipes based on available ingredients.
- **Meal Planner**: Introduce a meal planning feature where users can schedule meals for the week.
- **Voice Search Integration**: Enable voice-based search functionality for hands-free access.
- **Multi-Language Support**: Add translation features for different languages to enhance global usability.

## License
This project is open-source and free to use. Feel free to contribute and enhance its functionality.

## Credits
Developed using the **MealDB API** and designed with **HTML, CSS, and JavaScript**. Special thanks to all contributors and open-source resources that made this project possible.