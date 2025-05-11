# First Astro App

## Overview
This is a modern web application built using [Astro](https://astro.build/), a framework for building fast, content-focused websites. The project includes a variety of components, layouts, and utilities to create a responsive and interactive user experience.

## Features
- **Astro Framework**: Leverages Astro for static site generation and fast performance.
- **Custom Components**: Includes reusable UI components such as buttons, cards, and dropdown menus.
- **Dark Mode Toggle**: A `MoodToggle` component to switch between light and dark themes.
- **Responsive Design**: Ensures compatibility across devices with responsive layouts.
- **Global Styling**: Centralized styles managed in `global.css`.
- **Public Assets**: Includes images, icons, and a downloadable resume.

## Project Structure
```
astro.config.mjs          # Astro configuration file
components.json           # Component metadata
package.json              # Project dependencies and scripts
README.md                 # Project documentation
public/                   # Public assets (e.g., images, icons, resume)
src/                      # Source code
  components/             # Reusable UI components
  layouts/                # Layout files
  lib/                    # Utility functions
  pages/                  # Application pages
  styles/                 # Global and component-specific styles
```

### Key Directories
- **`src/components/`**: Contains reusable components like `Button` and `MoodToggle`.
- **`src/layouts/`**: Includes layout files such as `main.astro`.
- **`src/pages/`**: Application pages, including the homepage (`index.astro`).
- **`public/`**: Static assets like images and the downloadable resume.
- **`styles/`**: Global CSS styles.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd first-astro-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Usage
- Access the application at `http://localhost:3000` after starting the development server.
- Modify components or pages in the `src/` directory to customize the app.

## Components
### Button
Reusable button component with customizable styles.

### MoodToggle
A theme toggle component to switch between light and dark modes.

### Card
A card component for displaying content in a structured format.

## Deployment
To build the project for production:
```bash
npm run build
```
The output will be in the `dist/` directory, ready for deployment.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## Contact
For questions or feedback, please contact Abdullah Farhan Safwi.
