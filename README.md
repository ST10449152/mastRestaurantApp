# MAST Restaurant App


## Student Details

- Name: Weylin R.
- Surname: Riches
- Group: 3
- Course: Introduction to Mobile Aplications and Web Development
- [@Weylin Riches](https://github.com/ST10449152)

## Purpose and Key Features
Login System: The application starts with a login screen. To access the further portions of the software, users must input a predefined username (CHEF CHRISTOFFEL). A simple security measure to guarantee that only authorized users can add or modify the menu items is this login gate.


## Documentation

## Menu Display: 
After logging in, a list of menu items containing information about the name, description, price, and type of course is presented to the user. A notification titled "Empty Menu" appears if no items have been added. Additionally, the app counts how many things there are in the list overall.

## Adding Menu Items:
A button can be clicked by the user to create a new menu item. This brings users to a form where they may submit the name, description, price, and select the course type (e.g., appetizer, dessert) using a dropdown menu (Picker). The user is brought back to the main menu display after the new dish has been saved and added to the list.

## Functionalities and Flow
The application makes use of state variables to control a variety of features, including the menu list, login status, user input (for the menu item form), and whether or not the user is adding new items.
The menu item form has sections for the dish's name, description, and cost in addition to a Picker that allows the user to choose a course type from a list of pre-defined options (such as "appetizer" or "dessert"). The software verifies the inputs to make sure all needed fields are filled in and the price is a real amount before saving a new item.
The software determines the total number of menu items and dynamically updates the list upon the addition of a new item.


## Structure
The three primary screens of the app are the login screen, the menu display screen, and the add menu item screen. Depending on the application's current state—namely, whether the user is signed in or adding new items—these displays are conditionally shown.
Custom fonts supplied from Google Fonts give the styling a refined appearance, and styling is implemented using React Native's StyleSheet. With a dark tone, the app's UI is high contrast and contemporary, with hues like gold (#ffd700) for headers and white for text.

## Acknowledgements

 - [WebstaurantStore](https://www.webstaurantstore.com/)
 - [React Native](https://reactnative.dev/)
 - [Typescript](https://www.typescriptlang.org/)
