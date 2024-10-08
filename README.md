## Movie App Project

This project is a React-based movie application that allows users to view and edit movie details. It was developed following the instructions from *Fundamentals of Web Development (3rd Edition)*. 

### Exercise Overview

The goal of this exercise is to implement various React components to display a list of movies and allow for user interactions. The key components include:

- **MovieList**: Renders a list of movies by mapping over the provided movie data and generating a `SingleMovie` component for each entry.
- **SingleMovie**: Displays details for an individual movie, using props to dynamically render information from the passed movie object.
- **MovieLink**: A functional component that provides a link to the movie's page on The Movie Database (TMDb) using the movie's `tmdbID`.

### Steps Completed

1. **Component Implementation**: Completed the `MovieList`, `SingleMovie`, and `MovieLink` components.
2. **Rendering MovieList**: Integrated the `MovieList` component into the main `App` component, passing in the movie data stored in state.
3. **Dynamic Rendering**: Used the `map()` method to render `SingleMovie` components and to display a `MovieForm` for editing each movie's details.
4. **Controlled Components**: Implemented `MovieForm` as a controlled form component, ensuring user inputs are managed within React state.
5. **State Management**: Developed a `saveChanges` method in the `App` component to handle updates to the movie data, enabling real-time editing.

### Technologies Used

- React
- JavaScript
- HTML/CSS

This project serves as a practical application of fundamental React concepts, including component composition, state management, and event handling.
