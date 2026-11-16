# SpendWise - Personal Finance Tracker

## Project Description
SpendWise is a responsive web application designed to help users track daily expenses, monitor budgets, and visualize spending habits with clean data organization and intuitive UI design.

## Technologies Used
* **HTML5** – Semantic document structure
* **CSS3 / Flexbox / Grid** – Styling, responsive layouts, and modern UI components
* **JavaScript (ES6+)** – DOM manipulation, state management, and local storage persistence
* **Git & GitHub** – Version control and source code hosting
* **Netlify** – Continuous deployment and cloud hosting platform

## GitHub Repository Information
* **Repository URL:** https://github.com/isaackunda-web/spendwise-project-week7webdevelopment.git

## Live Netlify Website URL
* **Live Demo:** https://app.netlify.com/teams/isaac-idriss/projects

## Deployment Process Summary
1. Organized project assets and verified that `index.html` was located in the root directory.
2. Initialized a local Git repository, committed project files, and pushed the code to a public GitHub repository.
3. Connected the GitHub repository to Netlify via continuous integration.
4. Configured publish settings and deployed the static build.
5. Customized the Netlify subdomain to a meaningful project name and verified automated builds via git push updates.

## Challenges Encountered During Deployment
* **Asset Path Resolution:** Initially encountered broken image links because relative paths referenced local absolute directories rather than relative paths. Resolved by standardizing asset paths (`./assets/...`).
* **Build Configuration:** Ensured the root publish directory matched the output folder correctly so Netlify could serve `index.html` immediately.

## Lessons Learned
* Learned how seamless CI/CD pipelines function by linking GitHub repositories directly to cloud hosting providers like Netlify.
* Gained hands-on experience troubleshooting relative paths and structuring web projects for production environments.