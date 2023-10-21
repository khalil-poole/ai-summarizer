# Accessing the API for Developers Testing

1. Go to https://rapidapi.com/restyler/api/article-extractor-and-summarizer and either login or signup with your GitHub account.

2. Go to the Basic option, then click Subscribe for the free service, up to 100 requests can be made per month.

3. Click "Endpoints", then at the bottom click "GET /summarize". You can also test with the "Test Endpoint" button to ensure the API is currently working.

4. At the bottom right, click the "Code Snippets" option, and there you should be able to find your personal API key right beside where it says X-RapidAPI-Key.

5. Copy the API key, go to the .env file, and then paste your API key where it says "VITE_RAPID_API_ARTICLE_KEY=" no quotations are needed after the equals sign.

6. Save the file, then test the app, ensuring that you already have nodeJS installed. Open a new terminal within the root folder, followed by entering the "npm run dev" command.

# Potential Warnings

After pulling the repository, if the user has warnings for the CSS files, the app will work regardless.

For anyone in the future, if you are working in VSCode, you need to disable the lint rule of unknownAtRules.

Create .vscode at the root of your project
Create file named settings.json
Identify the filetype you are using for example css or scss
Create an empty json object {}
Inside json object add, "[FILE EXTENSION OF STEP 3].lint.unknownAtRules": "ignore"

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
