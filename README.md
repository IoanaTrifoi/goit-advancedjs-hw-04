GoIT Advanced JS - Homework 08: Image Search with Pagination
This project is an advanced image search application that utilizes the Pixabay API. It focuses on modern JavaScript techniques including Async/Await, Axios for HTTP requests, and Pagination.

Features
Async/Await Syntax: All asynchronous operations are handled using the modern async/await pattern for cleaner and more readable code.

Axios Integration: Used for reliable HTTP requests to the Pixabay backend.

Pagination (Load More): Search results are limited to 15 items per page. Users can load additional results using a "Load more" button.

Smooth Scrolling: The application automatically scrolls the page when new content is loaded, enhancing the user experience.

Interactive Lightbox: Integrated with SimpleLightbox for high-quality image previews in a modal window.

User Feedback:

Loading indicators during fetching.

iziToast notifications for empty results, errors, or reaching the end of the collection.

Project Structure
pixabay-api.js: Logic for API requests using Axios and async/await.

render-functions.js: Functions for DOM manipulation, rendering cards, and handling UI states (loader, buttons).

main.js: Main application logic coordinating the search and pagination flow.

Getting Started
Clone the repository:

Bash
git clone https://github.com/IoanaTrifoi/goit-advancedjs-hw-04.git
Install dependencies:

Bash
npm install
Run development server:

Bash
npm run dev
🔗 Links
Live Page: https://ioanatrifoi.github.io/goit-advancedjs-hw-04/

Source Code: https://github.com/IoanaTrifoi/goit-advancedjs-hw-04
