# College Information Page

This is a single-file web project.

## Run locally with XAMPP
1. Install XAMPP.
2. Put the project file inside `C:\xampp\htdocs\<folder>\`.
3. Start Apache. For PHP/MySQL projects, also start MySQL.
4. Open `http://localhost/<folder>/<file>`.

## GitHub
Upload the project file and README to a GitHub repository.

**Important:** GitHub Pages does not execute PHP. PHP/MySQL projects need PHP hosting and a MySQL database. Static HTML projects can run on GitHub Pages.

## Database
For projects using MySQL, the PHP file automatically creates its database and table on first run. For production, use environment variables:
`DB_HOST`, `DB_USER`, `DB_PASS`, `DB_NAME`.

Do not commit production passwords or secrets to GitHub.
