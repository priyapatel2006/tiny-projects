# React & Next.js Practice Projects for Beginners

This guide provides a list of simple yet effective projects to help you practice the fundamentals of React and Next.js. Each project includes a description, key concepts you'll learn, a list of features to implement, and a simple UI mockup to visualize the end result.

---

## Project 1: To-Do List App

A classic beginner project to master state management and user interactions.

### Description
A simple application where a user can add tasks to a list, mark them as complete, and remove them.

### Core Concepts to Learn
- **State Management:** Using the `useState` hook to manage the list of todos.
- **Handling User Input:** Capturing text from an input field.
- **Event Handling:** Responding to button clicks (`onClick`).
- **Rendering Lists:** Using `.map()` to display the list of tasks.
- **Conditional Rendering/Styling:** Changing the appearance of a task when it's marked as complete.

### Features to Implement
- [ ] Add a new task to the list.
- [ ] Display all current tasks.
- [ ] Mark a task as "completed" by clicking on it.
- [ ] Delete a task from the list using a delete button.
- [ ] The input field should clear after a task is added.

### Example UI Mockup
```
+-------------------------------------------+
|                My To-Do List              |
+-------------------------------------------+
|                                           |
|  Add a new task: [ Learn React    ] [Add]  |
|                                           |
|  ---------------------------------------  |
|                                           |
|  [ ] Finish project report      [Delete]  |
|  [x] ~~Go grocery shopping~~    [Delete]  |
|  [ ] Walk the dog               [Delete]  |
|                                           |
+-------------------------------------------+
```

---

## Project 2: Simple Weather App

This project introduces you to working with external data by fetching it from an API.

### Description
An app that allows a user to search for a city and see the current weather conditions. You can use a free API like [OpenWeatherMap](https://openweathermap.org/api).

### Core Concepts to Learn
- **Fetching Data:** Using `fetch()` or `axios` inside a `useEffect` hook.
- **API Integration:** Making requests to a third-party API.
- **State Management:** Storing fetched data, loading status, and errors.
- **Asynchronous Operations:** Managing what happens while data is being fetched.

### Features to Implement
- [ ] An input field for the user to type a city name.
- [ ] A "Search" button to trigger the API call.
- [ ] Display a "Loading..." message while fetching data.
- [ ] Display the city name, temperature, and a short description (e.g., "Clear Sky").
- [ ] Handle and display an error message if the city is not found.

### Example UI Mockup
```
+-------------------------------------------+
|               Weather Now                 |
+-------------------------------------------+
|                                           |
|  Enter City: [ London          ] [Search] |
|                                           |
|  ---------------------------------------  |
|                                           |
|             London, UK                    |
|             15°C                          |
|             ☁️ Broken Clouds              |
|                                           |
+-------------------------------------------+
```

---

## Project 3: Basic E-commerce Product Page

This project builds on components, props, and managing quantity state.

### Description
A single page that displays product details. The user should be able to increase or decrease the quantity they want to add to a cart.

### Core Concepts to Learn
- **Components & Props:** Creating a reusable `Product` component.
- **State Management:** Using `useState` to manage the product quantity.
- **UI Interaction:** Updating the UI when the user clicks increment/decrement buttons.

### Features to Implement
- [ ] Display a product image, title, price, and description.
- [ ] Show a quantity counter that starts at 1.
- [ ] Include "+" and "-" buttons to change the quantity.
- [ ] The quantity should not go below 1.
- [ ] An "Add to Cart" button that shows an alert with the selected quantity.

### Example UI Mockup
```
+-------------------------------------------------------------+
|  Product Page                                               |
+-------------------------------------------------------------+
|                                                             |
|  +---------------+  Classic T-Shirt                         |
|  |               |                                           |
|  | Product Image |  $15.99                                   |
|  |               |                                           |
|  +---------------+  A comfortable and stylish t-shirt.       |
|                     -----------------------------------       |
|                     Quantity:                                 |
|                     < [ - ]    [  1  ]    [ + ] >             |
|                                                             |
|                     [       Add to Cart       ]             |
|                                                             |
+-------------------------------------------------------------+
```

---

## Project 4: Simple Calculator

A great project for practicing logic and handling a more complex state.

### Description
A basic four-function calculator that can perform addition, subtraction, multiplication, and division.

### Core Concepts to Learn
- **State Management:** Handling the current display value, the previous value, and the selected operator.
- **Event Handling:** Managing clicks for number, operator, and action buttons (like 'C' for clear).
- **UI Layout:** Using CSS Grid or Flexbox to create the calculator layout.
- **Logic:** Implementing the calculation logic based on user input.

### Features to Implement
- [ ] A grid of number buttons (0-9).
- [ ] Buttons for basic operators (+, -, *, /).
- [ ] A "Clear" (C) button to reset the state.
- [ ] An "Equals" (=) button to perform the calculation.
- [ ] A display screen to show the current input and the result.

### Example UI Mockup
```
+-----------------+
| [ 0             ] | Display
+-----------------+
| [ 7 ] [ 8 ] [ 9 ] |
| [ 4 ] [ 5 ] [ 6 ] |
| [ 1 ] [ 2 ] [ 3 ] |
| [ C ] [ 0 ] [ = ] |
+-----------------+
```

---

## Project 5: Quote Generator

A quick and fun project to practice API calls on button click.

### Description
A simple app that displays a random quote and its author, fetched from an API. You can use an API like [Quotable](https://github.com/lukePeavey/quotable).

### Core Concepts to Learn
- **API Fetching:** Calling an API to get data.
- **`useEffect` Hook:** Fetching a quote when the component first loads.
- **Event Handling:** Fetching a new quote when a button is clicked.
- **State Management:** Storing the current quote and author.

### Features to Implement
- [ ] Display a random quote and its author on page load.
- [ ] A "New Quote" button that fetches and displays a new quote.
- [ ] A loading message while the quote is being fetched.

### Example UI Mockup
```
+-------------------------------------------+
|            Random Quote Machine           |
+-------------------------------------------+
|                                           |
|   "The only way to do great work is to     |
|    love what you do."                      |
|                                           |
|                   - Steve Jobs            |
|                                           |
|   [        New Quote        ]             |
|                                           |
+-------------------------------------------+
```

---

## Project 6: Quiz App

Test your knowledge on state management for scores and question indexes.

### Description
A simple multi-choice quiz application that presents a series of questions to the user and shows their final score at the end.

### Core Concepts to Learn
- **State Management:** Tracking the current question index and the user's score.
- **Conditional Rendering:** Showing the quiz questions or the final score screen.
- **Data Structures:** Storing quiz questions and answers in an array of objects.
- **User Feedback:** Highlighting the correct/incorrect answer after a user makes a choice.

### Features to Implement
- [ ] Display one question at a time with multiple-choice options.
- [ ] When an answer is clicked, show feedback (correct/incorrect).
- [ ] Move to the next question after an answer is chosen.
- [ ] At the end of the quiz, display the final score (e.g., "You got 3 out of 5 correct!").

### Example UI Mockup
```
+-------------------------------------------+
|                 React Quiz                |
|           Score: 2 | Question: 3/5        |
+-------------------------------------------+
|                                           |
|   What is the capital of France?          |
|                                           |
|   [ A) Berlin ]                           |
|   [ B) Madrid ]                           |
|   [ C) Paris  ]  <- User clicks this      |
|                                           |
+-------------------------------------------+
```

---

## Project 7: Character Counter

A small utility to practice controlled components and real-time UI updates.

### Description
A text input field (like a `textarea`) that shows a running count of the number of characters typed, similar to the Twitter post composer.

### Core Concepts to Learn
- **Controlled Components:** The `textarea` value is controlled by React state.
- **`onChange` Event:** Updating the state on every keystroke.
- **State Management:** Storing the text content from the `textarea`.
- **Conditional Styling:** Changing the text color of the counter when a limit is approached or exceeded.

### Features to Implement
- [ ] A `textarea` for user input.
- [ ] A counter that updates in real-time.
- [ ] A maximum character limit (e.g., 280).
- [ ] The counter text color should turn red if the user exceeds the limit.

### Example UI Mockup
```
+-------------------------------------------+
|              Tweet Composer               |
+-------------------------------------------+
|                                           |
|   [ This is a great example of a simple|
|     React project!                     ]  |
|                                           |
|                            48 / 280       |
|                                           |
+-------------------------------------------+
```

---

## Project 8: Digital Clock

An excellent project for understanding the `useEffect` hook and timers.

### Description
A component that displays the current time and updates every second without needing a page refresh.

### Core Concepts to Learn
- **`useEffect` Hook:** To set up and clean up a timer.
- **JavaScript Timers:** Using `setInterval()` to run a function repeatedly.
- **Component Lifecycle:** Understanding how `useEffect`'s cleanup function works when the component unmounts.
- **Date Object:** Working with JavaScript's `new Date()` to get the current time.

### Features to Implement
- [ ] Display the current time (hours, minutes, seconds).
- [ ] The time should update automatically every second.
- [ ] Format the time to be user-friendly (e.g., `10:30:45 AM`).

### Example UI Mockup
```
+-------------------------------------------+
|                Current Time               |
+-------------------------------------------+
|                                           |
|             10:30:45 AM                   |
|                                           |
+-------------------------------------------+
```

---

## Project 9: FAQ Accordion

Practice conditional rendering and managing the state of multiple components.

### Description
A list of frequently asked questions where clicking a question reveals its answer. Clicking another question collapses the previously opened one.

### Core Concepts to Learn
- **State Management:** Keeping track of which accordion item is currently active or open.
- **Conditional Rendering:** Showing or hiding the answer panel based on the active state.
- **Component Props:** Creating a reusable `AccordionItem` component that takes a question and answer as props.

### Features to Implement
- [ ] A list of questions.
- [ ] Clicking a question expands to show the answer.
- [ ] Clicking an already open question collapses it.
- [ ] (Optional) Only allow one question to be open at a time.

### Example UI Mockup
```
+-------------------------------------------+
|         Frequently Asked Questions        |
+-------------------------------------------+
|                                           |
|  [+] What is React?                       |
|  ---------------------------------------  |
|  [-] Why use Next.js?                     |
|      Next.js is a React framework that    |
|      provides production features...      |
|  ---------------------------------------  |
|  [+] Is JavaScript hard to learn?         |
|                                           |
+-------------------------------------------+
```

---

## Project 10: Recipe Finder App

A fun app that combines API fetching with user search functionality.

### Description
A web app where users can search for recipes. The app will fetch data from a free recipe API like [TheMealDB](https://www.themealdb.com/api.php) and display the results.

### Core Concepts to Learn
- **API Fetching with Search Params:** Constructing API request URLs based on user input.
- **Handling Form Submission:** Triggering the API call when the user submits the search form.
- **Displaying Grid Data:** Mapping over the results to display a grid of recipe cards.
- **State Management:** Handling the search query, search results, and loading state.

### Features to Implement
- [ ] A search bar and a "Find Recipes" button.
- [ ] Display search results in a grid layout, showing the recipe image and name.
- [ ] Show a message if no recipes are found for the search term.

### Example UI Mockup
```
+-------------------------------------------+
|               Recipe Finder               |
+-------------------------------------------+
|  Search for a dish: [ Chicken   ] [Find]  |
|  ---------------------------------------  |
|                                           |
|  +-----------+  +-----------+  +---------+ |
|  | [Image]   |  | [Image]   |  | [Image] | |
|  | Recipe 1  |  | Recipe 2  |  | Recipe 3| |
|  +-----------+  +-----------+  +---------+ |
|                                           |
+-------------------------------------------+
```
