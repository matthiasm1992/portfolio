# Web Development Practical Activity

## Building Your First Web Page

Hello! Today you'll learn how to create your first web page using HTML and CSS. We'll create a simple personal profile page that includes images, links, and styling.

### What You'll Learn

Basic HTML document structure
How to add and style images
How to create hyperlinks
How to apply CSS styling

### Step 1: Creating the Basic HTML Structure

First, create a new file called index.html. Copy this basic HTML structure.

#### Example HTML code:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile Page</title>
</head>
    <body>
    </body>
</html>
```

This is your basic HTML template. The <head> section contains information about your document, while the <body> section contains the content that will be visible on your page.

### Step 2: Adding Content and Images

Let's add some content inside the <body> tag. We'll create a heading and add some text about yourself.

Example HTML code:

```
<body>
    <h1>Welcome to My Profile</h1>
        <!-- Adding an image -->
    <img src="https://placekitten.com/300/200" alt="Profile picture">
        <h2>About Me</h2>
    <p>Hello! I'm learning web development. This is my first webpage where I'm practicing HTML and CSS.</p>
</body
```

Important notes about images:

- The src attribute tells the browser where to find the image
- The alt attribute provides alternative text for accessibility
- Replace the placeholder URL with your own image URL

### Step 3: Adding Hyperlinks

Let's add some links to your favorite websites.

#### Example HTML code:

```
<h2>My Favorite Websites</h2>
<ul>
    <li><a href="https://www.github.com" target="_blank">GitHub</a></li>
    <li><a href="https://www.wikipedia.org" target="_blank">Wikipedia</a></li>
</ul>
```

#### **Link tips:**

- **href** specifies where the link goes
  `target="_blank"` makes the link open in a new tab
- Always include the full URL including **'https://'**

### Step 4: Adding CSS

Now let's make it look nice! Add this `<style>` section in your `<head>`.

#### Example HTML code:

```
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile Page</title>
    <style>
        /* Making the body look nice */
        body {
            font-family: Arial, sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f0f0f0;
        }

        /* Styling the headings */
        h1 {
            color: #2c3e50;
            text-align: center;
        }

        /* Making the image responsive */
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px auto;
            border-radius: 8px;
        }

        /* Styling the links */
        a {
            color: #3498db;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Styling paragraphs */
        p {
            line-height: 1.6;
            color: #333;
        }
    </style>
</head>
```

You can see the complete example on GitHub by clicking this [link](https://github.com/ITonlinelearning-code/CodingProgramme-HTML-CSS/blob/main/HTML_02_01_building_your_first_website/index.html)!

## Important: Showcase Your Work!

Before you move onto the next lesson, please ensure you create a GitHub account if you haven't already. GitHub will be your coding journey's digital footprint – a place where potential employers can see your growth and capabilities.

## Why This Matters

Every piece of code you write during this course and programme is more than just a learning exercise; it's evidence of your developing skills. By committing your practical activities to GitHub:

- You'll build a comprehensive record of your progress
- You'll develop good version control habits
- Future employers can see your real-world coding abilities
- You'll have a backup of all your work

## Starting Your Portfolio

This is also the perfect time to start building your portfolio website. A well-crafted portfolio:

- Showcases your best projects
- Demonstrates your technical abilities
- Helps you stand out in job applications
- Provides a professional online presence

**Remember:** The projects you'll create in this course can form the foundation of your portfolio. Start documenting your journey now – your future self will thank you!
