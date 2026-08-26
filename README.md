GDMC BOT — GitHub Pages MVP
A professional static website + interactive maintenance governance dashboard for GDMC BOT.
Included
Public landing page
Control Center dashboard
Five approved maintenance statuses
Search and status filtering
Demo request creation
Responsive mobile layout
GitHub Actions deployment to GitHub Pages
Deploy
Create a new GitHub repository, e.g. `gdmc-bot`.
Upload all files from this project to the repository root.
Commit to `main`.
Open Settings → Pages → Build and deployment.
Set Source = GitHub Actions.
Open Actions and wait for the deployment to finish.
GitHub Pages will provide the live URL.
GitHub Pages is static hosting. This MVP stores demo data in browser memory only. For production, connect the dashboard to a real backend/database and never put API secrets in frontend code.
Production roadmap
WhatsApp API → Make → secure backend/database → dashboard → notifications → reports.
