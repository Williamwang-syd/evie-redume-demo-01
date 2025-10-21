# evie-redume-demo-01

🛠 Step 1: Set up your GitHub repo
Go to GitHub and create a new repository.

Name it something like job-board-demo.

Choose Public (easier for free hosting).

Initialize with a README.


🖊 Step 2: Create your landing pages
Since you want just a few pages, we’ll use plain HTML + CSS + a little JS (no heavy framework needed).


🌐 Step 3: Edit online
Open your repo in GitHub Codespaces or VS Code for the Web (https://vscode.dev/github/<your-username>/<repo>).

Add the index.html, jobs.html, about.html, and assets folder.

Commit and push.

🚀 Step 4: Deploy to Azure Static Web Apps
Go to the Azure Portal.

Create a Static Web App.

Choose the Free plan.

Connect it to your GitHub repo.

For “Build Presets,” select Custom (since it’s plain HTML).

Set App location = / (root).

Leave build/output empty.

Azure will create a GitHub Actions workflow in your repo.

Within a minute or two, your site will be live at a *.azurestaticapps.net URL.


🎯 Step 5: Polish
Add a jobs.html page with a simple job listing table.

Add an about.html page with your project description.

Push changes → GitHub Actions redeploys automatically.