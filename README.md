# nextjs-coding-test

## Introduction
This is a sample next js project for coding test.

## Coding Test
- **Time**: You have 1 hour to complete this test.
- **Objective**: Build a simple "User Profile" component and a "User List" component with a basic layout and some interactivity.
- **Requirements**:
  - **User Profile Component**: Displays a single user's details (name, age, occupation).
  - **User List Component**: Shows a list of users and allows users to be selected for viewing details in the User Profile component.
  - **Styling**: Apply minimal styling to ensure the components are visually distinguishable and responsive.

## Project Outline
1. **User Profile Component** (UserProfile.js):
	- **Props**: name, age, occupation
	- **Functionality**: Display user information in a card layout.
	- **Styling Requirement**: Style the component with basic CSS (e.g., a border, padding, and background color).
2. **User List Component** (UserList.js):
	- **Props**: users (an array of user objects)
	- **Functionality**: Display each user’s name in a list format. When a user’s name is clicked, display that user's details in the UserProfile component.
	- **Styling Requirement**: Style the list with simple CSS (e.g., add hover effects for each list item).
3. **Main Page** (index.js):
	- Import and use the UserList and UserProfile components.
	- Provide an array of sample users (hardcoded or generated).
	- Implement basic state management to display the selected user's details in the UserProfile component.