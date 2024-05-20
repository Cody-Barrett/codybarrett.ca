## Overview
This is the repository for my personal website, built using Tailwind CSS, Vite, and Svelte, and hosted on GitHub Pages. The site is built and deployed automatically using GitHub Actions.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Development](#development)
- [Deployment](#deployment)

## Features
- **Responsive Design**: Uses Tailwind CSS for a mobile-first, responsive design.
- **Modern JavaScript**: Built with Vite for a fast and optimized development experience.
- **Component-Based Architecture**: Utilizes Svelte for building reusable components.
- **Continuous Deployment**: Automatically built and deployed to GitHub Pages using GitHub Actions.

## Technologies Used
- **[Tailwind CSS](https://tailwindcss.com/)**: Utility-first CSS framework.
- **[Vite](https://vitejs.dev/)**: Next-generation frontend tooling.
- **[Svelte](https://svelte.dev/)**: Cybernetically enhanced web apps.
- **[GitHub Pages](https://pages.github.com/)**: Host websites directly from a GitHub repository.
- **[GitHub Actions](https://github.com/features/actions)**: Automate workflows for CI/CD.

## Getting Started
### Prerequisites
- Node.js and npm installed on your local machine.
- Git installed on your local machine.

### Installation
1. **Clone the repository:**
    ```
    git clone https://github.com/Cody-Barrett/codybarrett.ca.git
    ```
2. **Navigate to the project directory:**
    ```
    cd codybarrett.ca
    ```
3. **Install dependencies:**
    ```
    npm install
    ```

## Development
1. **Run the local development server:**
    ```
    npm run dev
    ```
2. **Open your browser and navigate to:**
    ```
    http://localhost:5173
    ```

## Deployment
The website is deployed automatically using GitHub Actions. Whenever changes are pushed to the `main` branch, the workflow defined in `.github/workflows/main.yml` is triggered to build and deploy the site to GitHub Pages.