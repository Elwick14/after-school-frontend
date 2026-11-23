# After School Classes - Front-End (Vue.js)

Front-end for the After School Classes web app (CST3144 coursework).
Built with Vue.js 3, Bootstrap and Font Awesome. Data is fetched from the Express.js back-end using `fetch`.

## Links

- [Vue.js App] GitHub repository: https://github.com/Elwick14/after-school-frontend
- [Vue.js App] GitHub Pages (the app running): https://elwick14.github.io/after-school-frontend/
- [Express.js App] GitHub repository: https://github.com/Elwick14/after-school-backend
- [Express.js App] render.com route that returns all the lessons: https://m01147721-after-school-backend.onrender.com/lessons

## Features

- List of lessons with subject, location, price, spaces and an icon
- Sort by subject, location, price or spaces, ascending or descending
- Add to cart, with remaining spaces updating
- Cart page with remove
- Checkout with validated name (letters only) and phone (numbers only)
- Orders saved with POST, lesson spaces updated with PUT