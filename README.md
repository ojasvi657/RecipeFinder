# Colorful Recipe Finder

A vibrant and user-friendly web application to find delicious recipes from around the world with a special focus on Indian cuisine.  
Users can search recipes by keyword or quickly browse Indian recipes using the dedicated toggle button. Full recipe details including ingredients and instructions are displayed in a modern, accessible modal.

---

## Features

- **Colorful, vibrant UI:** Modern design with bright gradients and smooth interactions for a delightful user experience.
- **Search recipes:** Search by any keyword, such as "chicken", "pasta", or "dessert".
- **Indian recipes toggle:** Instantly browse a curated selection of Indian recipes.
- **Recipe details modal:** View recipe image, category, cuisine, ingredients list, and cooking instructions in a pop-up modal.
- **Responsive design:** Works beautifully across mobile, tablet, and desktop screens.
- **Accessibility:** Keyboard navigable recipe cards and modal, ARIA roles and labels, focus management.

---

## How It Works

The app uses the free [TheMealDB API](https://www.themealdb.com/api.php) to fetch recipe data.

- **Search API:** Fetches recipes matching the search term with detailed info.
- **Filter by Area:** Fetches Indian recipes by area filter and loads full recipe details on demand.
- Recipe cards are clickable and keyboard accessible, opening a modal with full details.

---

## Usage

1. Open `recipe-finder.html` in any modern browser.
2. Enter a keyword in the search box and press **Search** or hit **Enter**.
3. Click recipe cards to view full details.
4. Alternatively, click **Show Indian Recipes** to browse Indian cuisine quickly.
5. Close the detail modal by clicking the close button, pressing **Escape**, or clicking outside the modal.

---

## Technologies Used

- HTML5 & CSS3 (Flexbox & Grid)
- Modern JavaScript (ES6+)
- [TheMealDB Public API](https://www.themealdb.com/api.php)
- Responsive & accessible web design principles

---

## Accessibility Features

- All interactive elements are keyboard focusable.
- Modal uses ARIA roles for dialog and manages keyboard focus.
- High contrast and readable font sizes.
- Clear visible focus states on interactive elements.

---

## Folder Structure

- `recipe-finder.html` — Complete single-page web app with inline styles and scripts.
- `README.md` — Project documentation.

---

## Deployment

Since it is a static HTML file using a public API, you can simply host `recipe-finder.html` on any static hosting platform or open directly in a browser.

---

## License

This project is open source.

---

## Acknowledgements

- Recipe data provided by [TheMealDB](https://www.themealdb.com)
- Colorful design inspired by modern food and recipe websites

---

Enjoy cooking and discovering tasty recipes with the Colorful Recipe Finder!  
Feel free to contribute or suggest improvements.

