#HTML
mkdir MyHTMLProject
cd MyHTMLProject
touch index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My HTML Project</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; }
    .box { padding: 20px; border: 2px solid #3498db; border-radius: 10px; }
  </style>
</head>
<body>
  <div class="box">Hello, GitHub!</div>
</body>
</html>
touch README.md
# MyHTMLProject

A simple HTML project demonstrating a styled box.

## How to view
Open `index.html` in your browser to see the result.
touch .gitignore
*.log
*.tmp
git init
git add .
git commit -m "Initial commit with HTML project and README"
MyHTMLProject
git remote add origin <your-github-repo-url>
git branch -M main
git push -u origin main
