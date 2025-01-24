# QuickRabbit

QuickRabbit is a responsive webpage that showcases various fields or topics, each represented by a clickable box. The design ensures that the boxes fit neatly within the page without clumping and adjust automatically to different screen sizes using CSS Grid.

## Features

- Responsive design using CSS Grid
- Dynamic search functionality
- Links to external resources and social media
- Interactive hover effects

## Files

1. **index.html**: The main HTML file containing the structure of the webpage.
2. **candy1.css**: An external CSS file for additional styling (not included here but referenced in the HTML).
3. **README.md**: This file, providing an overview and instructions.

## Code Overview

### HTML Structure

The HTML file includes a header, a search bar, and a grid of boxes. Each box represents a different field or topic and links to an external page.

- **Header**: Contains the title and logo of QuickRabbit.
- **Search Bar**: Allows users to search for specific fields.
- **Boxes**: Represent different fields/topics and are clickable, leading to external pages.

### CSS

The CSS provided in the `<style>` tag handles the layout and styling of the webpage. It includes:

- **Grid Layout**: Utilizes CSS Grid to create a responsive layout for the boxes.
- **Hover Effects**: Adds interactive hover effects to the search bar inputs and buttons.
- **Box Styling**: Ensures each box maintains a square aspect ratio and adjusts to the viewport size.

### JavaScript

The JavaScript functions enhance the interactivity of the webpage:

- **searchField()**: Filters the boxes based on the user's input in the search bar.
- **googleSearch()**: Opens a new tab with Google search results for the user's query.
- **chatbotSearch()**: Opens a new tab with search results from a chatbot service.
- **goToAboutUs()**: Navigates to the About Us page.
- **goToLinkedIn()**: Opens the LinkedIn homepage in a new tab.

## Usage

To use this webpage, open the `index.html` file in a web browser. The search bar allows users to filter the displayed boxes by typing in keywords. Clicking on any box will open a new tab with the relevant page. The buttons in the search bar provide additional functionality such as performing Google searches and accessing social media.

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

