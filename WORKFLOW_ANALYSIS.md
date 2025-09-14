## 1. What triggers this workflow to run?
This workflow runs when something gets pushed to the main branch.
## 2. What are the four main steps this workflow performs?
The four steps are checkout code, validate html, check for broken links, and deploy to GitHub Pages.
## 3. What does the "Checkout code" step do and why is it necessary?
Checkout code uses actions/checkout@v4 to get the code from the repository. This is necessary because without it, the actions won't have access to your project files.
## 4. What is the purpose of the environment configuration?
Environment configuration determines where the deployment will occur.
## 5. How does this automated deployment improve reliability compared to manual deployment?
This will ensure that everything occurs uniformly when it's deployed. It also removes human error from the deployment process and will make everything run smoother.
## 6. What would happen if you pushed code to a different branch (not main)?
Nothing would happen because the deployment is only triggered when something is pushed to main.