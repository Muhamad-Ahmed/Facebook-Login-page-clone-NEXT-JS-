# Facebook Login Page Clone

A professional clone of the Facebook login page built with [Tailwind CSS](https://tailwindcss.com/). This project demonstrates modern frontend techniques and utility-first CSS for rapid UI development.

## Screenshots

![Facebook Login Page Clone Screenshot](/public/project%20screenshot.png)

## Features

- Responsive design closely matching Facebook's login page
- Built with Tailwind CSS v4 for fast and maintainable styling
- Clean, semantic HTML structure
- Includes Facebook logo and favicon assets
- Accessible form fields and buttons

## Project Structure

```
.
├── public/
│   ├── facebook.png
│   └── facebookLogo.svg
├── src/
│   ├── index.html
│   ├── input.css
│   └── output.css
├── package.json
├── tailwind.config.js
└── .gitignore
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/ahmed-shahidd/Facebook-Login-page-clone-NEXT-JS-.git
   cd Facebook-Login-page-clone-NEXT-JS-
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Build Tailwind CSS:**
   ```sh
   npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
   ```
   This will generate/update `output.css` as you work.

4. **Open the project:**
   - Open `src/index.html` in your browser to view the login page.

## Customization

- **Tailwind Config:** Modify [`tailwind.config.js`](tailwind.config.js) to customize the theme or add plugins.
- **Assets:** Replace images in the [`public/`](public/) folder as needed.
- **HTML/CSS:** Edit [`src/index.html`](src/index.html) and [`src/input.css`](src/input.css) for further customization.



## License

This project is for educational and demonstration purposes only. All Facebook trademarks and logos are property of Meta Platforms, Inc.

---

**Made with ❤️ using Tailwind CSS**
