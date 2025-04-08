# React Reviews Carousel Project

An interactive component built with React to display and cycle through user reviews or testimonials. Users can navigate sequentially using previous/next buttons or view a random review with the "Surprise Me" button.

**[Live Demo](https://reviewcarouselnoto.netlify.app/)**

This component showcases reviews with a clean, card-based UI. Users can easily browse reviews sequentially or jump to a random one.

Key features include:

- Displays individual reviews with author details and review text, offering sequential and random navigation options.
- Styled with CSS custom properties for easy theming and uses React Icons for visual elements.

Technologies Used:

- React.js (with `useState` Hook)
- JavaScript (ES6+)
- CSS3 (with Custom Properties)
- `react-icons` library

## Project Setup

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    cd <repository-directory-name>
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    # or
    # yarn install
    ```

## Running the Project

- **Development Mode:**
  ```bash
  npm run dev
  # or if using Create React App:
  # npm start
  ```
  This will typically start the development server and open the application in your default browser at `http://localhost:5173` (Vite) or `http://localhost:3000` (CRA).

## Project Structure & Data

- **`src/App.jsx`:** Contains the main application logic, state management, and JSX structure for the review component.
- **`src/data.js`:** An array of review objects. Each object should contain:
  - `id`: Unique number
  - `name`: String (Author's name)
  - `job`: String (Author's job title)
  - `image`: String (URL to the author's image - **ensure these are stable URLs**)
  - `text`: String (The review content)
- **`src/index.css` (or similar):** Contains the global CSS and specific styles for the review component.

**Important Note on Images:** The `image` URLs in `data.js` need to point to stable, accessible image files. If using images generated from services like `thispersondoesnotexist.com`, you must save the desired images and host them somewhere that provides a permanent link (e.g., within your project's `public` folder or using an image hosting service).

## Potential Future Improvements

- Add smooth transitions/animations when changing reviews.
- Fetch review data from an external API instead of a local file.
- Implement error handling for image loading.
- Add accessibility improvements (e.g., ARIA attributes).

