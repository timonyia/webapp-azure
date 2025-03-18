# Azure Static Web App

This project is an Azure Static Web App that hosts a simple HTML page for the SmartAI Assistant. The application is designed to provide users with an interactive virtual assistant experience.

## Project Structure

- `src/index.html`: Contains the HTML structure, styles, and an embedded iframe for the SmartAI Assistant.
- `.github/workflows/azure-static-web-apps.yml`: GitHub Actions workflow configuration for deploying the Azure Static Web App.
- `package.json`: Configuration file for npm, listing dependencies and scripts for the project.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd azure-static-web-app
   ```

2. **Install Dependencies**
   If you have any dependencies listed in `package.json`, run:
   ```bash
   npm install
   ```

3. **Run the Application Locally**
   You can open the `src/index.html` file in your web browser to view the application locally.

## Deployment

This project is set up for deployment using GitHub Actions. When you push changes to the main branch, the workflow defined in `.github/workflows/azure-static-web-apps.yml` will automatically build and deploy the application to Azure.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.