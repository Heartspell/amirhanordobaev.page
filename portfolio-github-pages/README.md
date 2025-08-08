# Portfolio GitHub Pages

This project is a personal portfolio website for Amirhan Ordobaev, showcasing skills, projects, and contact information. The portfolio is designed to be deployed on GitHub Pages.

## Project Structure

```
portfolio-github-pages
├── src
│   ├── index.html       # Main HTML structure of the portfolio
│   └── style.css       # Styles for the portfolio
├── .github
│   └── workflows
│       └── deploy.yml   # GitHub Actions workflow for deployment
├── README.md            # Documentation for the project
└── package.json         # Configuration file for npm
```

## Getting Started

To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/portfolio-github-pages.git
   cd portfolio-github-pages
   ```

2. **Install dependencies:**
   If you have any dependencies listed in `package.json`, run:
   ```bash
   npm install
   ```

3. **Open the portfolio:**
   You can open `src/index.html` in your browser to view the portfolio locally.

## Deployment

This project uses GitHub Actions to automate the deployment to GitHub Pages. The deployment workflow is defined in `.github/workflows/deploy.yml`. 

Whenever you push changes to the `main` branch, the portfolio will be automatically deployed to GitHub Pages.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.