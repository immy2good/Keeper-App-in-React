# Keeper App in React

A React-based note-taking application inspired by Google Keep, built as part of the University of London BSc Computer Science coursework.

## Table of Contents

* [Demo](#demo)
* [Features](#features)
* [Tech Stack](#tech-stack)
* [Installation](#installation)
* [Running Locally](#running-locally)
* [Running Online](#running-online)
* [Deploying to GitHub Pages](#deploying-to-github-pages)
* [Project Structure](#project-structure)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

## Demo

**CodeSandbox (Live Demo)**
[https://codesandbox.io/s/keeperapp-part3-dwwpvm](https://codesandbox.io/s/keeperapp-part3-dwwpvm)

*Click the link above to view and run the app in your browser without any local setup.*

## Features

* **Create Notes**: Add new notes with titles and content.
* **Delete Notes**: Remove notes you no longer need.
* **Responsive Design**: Works on both desktop and mobile devices.
* **Local Persistence**: Notes are saved in the browser's Local Storage.
* **React Hooks**: Utilises `useState` and `useEffect` for state management and side effects.

## Tech Stack

* **React** (Create React App)
* **JavaScript (ES6+)**
* **CSS3**

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/immy2good/Keeper-App-in-React.git
   cd Keeper-App-in-React
   ```
2. **Install dependencies**

   ```bash
   npm install
   ```

## Running Locally

Start the development server and open the app in your browser:

```bash
npm start
```

By default, the app runs at `http://localhost:3000`.

## Running Online

### CodeSandbox

Use the live CodeSandbox link under [Demo](#demo).

### GitHub Pages

You can also host the built app directly from this repository using GitHub Pages:

1. **Add homepage to `package.json`**

   ```json
   {
     "homepage": "https://immy2good.github.io/Keeper-App-in-React"
   }
   ```
2. **Install the `gh-pages` package**

   ```bash
   npm install --save gh-pages
   ```
3. **Add deploy scripts to `package.json`**

   ```json
   {
     "scripts": {
       "predeploy": "npm run build",
       "deploy": "gh-pages -d build"
     }
   }
   ```
4. **Deploy to GitHub Pages**

   ```bash
   npm run deploy
   ```

After deployment, the app will be available at `https://immy2good.github.io/Keeper-App-in-React`.

Alternatively, you can enable Pages in GitHub settings (Settings → Pages) and select the `gh-pages` branch as the source.

## Deploying to GitHub Pages

The `npm run deploy` command (from above) will create a `gh-pages` branch and push the production build to it. GitHub Pages then serves the app automatically.

## Project Structure

```plaintext
Keeper-App-in-React/
├── public/
│   ├── index.html        # Main HTML file
│   └── favicon.ico       # App icon
├── src/
│   ├── components/       # Reusable React components
│   │   ├── Header.jsx    # App header and input form
│   │   ├── Note.jsx      # Individual note card
│   │   └── ...
│   ├── App.js            # Root component
│   ├── index.js          # Entry point
│   └── styles.css        # Global styles
├── package.json          # Project metadata & scripts
└── README.md             # This file
```

## Contributing

Contributions are welcome! Please follow these steps:

1. **Fork** the repository.
2. **Create** a feature branch:

   ```bash
   ```

git checkout -b feature/my-feature

````
3. **Commit** your changes:
```bash
git commit -m "Add my feature"
````

4. **Push** to your fork:

   ```bash
   ```

git push origin feature/my-feature

```
5. **Open** a Pull Request.

Please adhere to the existing code style and include clear commit messages.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

Developed by Immy (immy2good).

- GitHub: https://github.com/immy2good
- Email: your.email@example.com

```
