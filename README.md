# Library Management System — Frontend

Static HTML/CSS frontend prepared for Vercel deployment. PHP and database code are not included here.

## Deploy
1. Set `window.API_BASE_URL` in `assets/js/api.js` to your deployed PHP backend API URL, ending in `/api`.
2. Push this folder to a separate GitHub repository.
3. Import that repository into Vercel. Framework preset: Other; Root Directory: `library-frontend` if importing the parent folder, or leave root as `.` if this folder is the repository root.

The pages preserve the original supplied HTML and styling. They currently include demo/sample page content; connect each form and table to `LibraryAPI` methods in `assets/js/api.js` before using with live data.
