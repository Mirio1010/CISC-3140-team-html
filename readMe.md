# CISC 3140 - Team HTML Project

## Getting Started Guide

Hey team! This README will help you get set up and submit your HTML page. Don't worry if you're new to Git/GitHub - just follow these steps.

## Step 1: Get Access to the Repository

You should receive an email invitation to collaborate on this repository. Accept the invitation so you can push your changes.

## Step 2: Install Git (if you haven't already)

- **Windows/Mac/Linux**: Download from [git-scm.com](https://git-scm.com/downloads)
- Verify installation by opening terminal/command prompt and typing: `git --version`

## Step 3: Clone the Repository

1. Open your terminal/command prompt
2. Navigate to where you want the project folder:
```bash
   cd Desktop
```
3. Clone this repository:
```bash
   git clone [repository-url-here]
```
4. Move into the project folder:
```bash
   cd CISC-3140-team-html
```

## Step 4: Create Your HTML File

1. Navigate to the `teamHtml_files` folder
2. Create a new file named `yourname.html` (use your actual name, like `john.html`)
3. Use the template below if you'd like:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - CISC 3140</title>
</head>
<body>
    <h1>Your Name</h1>
    
    <h2>About Me</h2>
    <p>Write a short bio about yourself here.</p>
    
    <h2>My Hobbies</h2>
    <ul>
        <li>Hobby 1</li>
        <li>Hobby 2</li>
        <li>Hobby 3</li>
    </ul>
    
    <h2>Favorite Website</h2>
    <p>Check out my favorite website: <a href="https://example.com">Example Site</a></p>
    
    <img src="https://via.placeholder.com/300" alt="Description of image">
</body>
</html>
```
You can also add your CSS file for styling your page. Just add it to the 'styles' folder and link it to your html page using the link tag.

## Step 5: Push Your File to GitHub

1. Check what files you've changed:
```bash
   git status
```

2. Add your HTML file:
```bash
   git add teamHtml_files/yourname.html
```
or you can add all files like this(This is easier)

```
git add .
```

3. Commit your changes with a message:
```bash
   git commit -m "Add [your name]'s HTML page"
```

4. Push to GitHub:
```bash
   git push
```

## Common Issues

**"Permission denied" error**: Make sure you've accepted the collaborator invitation

**"Merge conflict"**: Pull the latest changes first with `git pull`, then try again

**Need to update your local copy**: Run `git pull` before making changes

## Need Help?

- Reach out in our group chat
- Check Git documentation: [git-scm.com/doc](https://git-scm.com/doc)
- GitHub guides: [guides.github.com](https://guides.github.com)

---

**Note**: I'll create the `index.html` file that links to everyone's pages once all team members have submitted their files.
