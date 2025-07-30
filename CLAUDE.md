# Jianu&company - Service Auto Profesional

This project is a professional car service website for Jianu&company, located in Motăței, Dolj.

## Project Structure

- `index.html`: The main HTML file containing the website structure, content, and inline CSS/JavaScript.
- `car.jpg`, `oil-change.jpg`, `tire.jpg`, `arseny-togulev-xTXIAVRI3rA-unsplash.jpg`, `photo-car.avif`, `photo-tools.jpeg`: Image assets used throughout the website.
- `package.json`, `package-lock.json`: Node.js package manager files, including `gh-pages` for deployment.

## Deployment

This project is deployed to GitHub Pages using the `gh-pages` npm package.

To deploy the project:

1.  Ensure all changes are committed to the `main` branch.
2.  Run the deploy script defined in `package.json`:
    ```bash
    npm run deploy
    ```

This command will build the project (if necessary, though for this static site it just copies files) and push the contents of the current directory to the `gh-pages` branch of your GitHub repository. GitHub Pages will then serve the website from this branch.

## Live Site

The live site can be accessed at the URL configured for your GitHub Pages, typically `https://<your-github-username>.github.io/<your-repository-name>/`.

For this project, the homepage is specified in `package.json` as `https://github.com/gergobalogh/jianu-auto-service#readme`, but the actual GitHub Pages URL will be `https://gergobalogh.github.io/jianu-auto-service/`.
