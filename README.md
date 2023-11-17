# Mr.Red's Website Template

# review the Web Site

# User Guide: Harun Yahya Aydın Web Page

This user guide explains step by step how to use the "Harun Yahya Aydın" web page.

## Table of Contents

1. [Getting Started](#getting-started)
2. [About Me Section](#about-me-section)
3. [Features Section](#features-section)
4. [End of the Page](#end-of-the-page)

---

## Getting Started

At the beginning of the webpage, there are essential elements that define the title, character set, and mobile device compatibility.

```html
<!DOCTYPE html>
<html lang="tr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link rel="stylesheet" href="style.css">
    <title>Harun Yahya Aydın</title>
</head>
```

- `charset`: Sets the character set of the page.
- `viewport`: Ensures proper display on mobile devices.
- `boxicons`: Stylesheet containing icons used on the page.
- `style.css`: Custom stylesheet.
- `title`: Page title.

---

## About Me Section

The About Me section includes personal information and contact options.

```html
<body>
    <header>
        <!-- ... -->
    </header>

    <section id="about">
        <div class="header">
            <h1>About Me</h1>
            <a href="mailto:harunyahya.aydin@outlook.com">Contact Me</a>
        </div>

        <div class="card">
            <!-- ... -->
        </div>
    </section>
```

- `header`: Section containing the page title.
- `section#about`: Beginning of the About Me section.
- `div.header`: About Me title and contact option.
- `div.card`: Card containing personal information and an image.

---

## Features Section

The Features section showcases the user's abilities and expertise.

```html
<section id="features">
    <div class="header">
        <h1>Features</h1>
    </div>
    <div class="feature-cards">
        <!-- ... -->
    </div>
</section>
```

- `section#features`: Beginning of the Features section.
- `div.header`: Features title.
- `div.feature-cards`: Section containing skill cards.

---

## End of the Page

At the end of the page, there's a button allowing users to quickly return to the top of the page.

```html
<button class="scroll-top" onclick="scrollToTop()">
    <i class='bx bxs-up-arrow'></i>
</button>
```

- `button.scroll-top`: Button for returning to the top of the page.
- `onclick="scrollToTop()"`: JavaScript function triggered when the button is clicked.

---

## Additional Notes

- Page design and style are defined in the `style.css` file.
- Page animations and background effects are provided through the `particles.js` and `script.js` files.

This guide should help you understand the basic structure and usage of the page. Feel free to modify the content or customize the HTML and CSS files to suit your needs.

--- 

Now, let me provide the same guide in Markdown format:

```markdown
# User Guide: Harun Yahya Aydın Web Page

This user guide explains step by step how to use the "Harun Yahya Aydın" web page.

## Table of Contents

1. [Getting Started](#getting-started)
2. [About Me Section](#about-me-section)
3. [Features Section](#features-section)
4. [End of the Page](#end-of-the-page)

---

## Getting Started

At the beginning of the webpage, there are essential elements that define the title, character set, and mobile device compatibility.

```html
<!DOCTYPE html>
<html lang="tr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link rel="stylesheet" href="style.css">
    <title>Harun Yahya Aydın</title>
</head>
```

- `charset`: Sets the character set of the page.
- `viewport`: Ensures proper display on mobile devices.
- `boxicons`: Stylesheet containing icons used on the page.
- `style.css`: Custom stylesheet.
- `title`: Page title.

---

## About Me Section

The About Me section includes personal information and contact options.

```html
<body>
    <header>
        <!-- ... -->
    </header>

    <section id="about">
        <div class="header">
            <h1>About Me</h1>
            <a href="mailto:harunyahya.aydin@outlook.com">Contact Me</a>
        </div>

        <div class="card">
            <!-- ... -->
        </div>
    </section>
```

- `header`: Section containing the page title.
- `section#about`: Beginning of the About Me section.
- `div.header`: About Me title and contact option.
- `div.card`: Card containing personal information and an image.

---

## Features Section

The Features section showcases the user's abilities and expertise.

```html
<section id="features">
    <div class="header">
        <h1>Features</h1>
    </div>
    <div class="feature-cards">
        <!-- ... -->
    </div>
</section>
```

- `section#features`: Beginning of the Features section.
- `div.header`: Features title.
- `div.feature-cards`: Section containing skill cards.

---

## End of the Page

At the end of the page, there's a button allowing users to quickly return to the top of the page.

```html
<button class="scroll-top" onclick="scrollToTop()">
    <i class='bx bxs-up-arrow'></i>
</button>
```

- `button.scroll-top`: Button for returning to the top of the page.
- `onclick="scrollToTop()"`: JavaScript function triggered when the button is clicked.

---

## Additional Notes

- Page design and style are defined in the `style.css` file.
- Page animations and background effects are provided through the `particles.js` and `script.js` files.

This guide should help you understand the basic structure and usage of the page. Feel free to modify the content or customize the HTML and CSS files to suit your needs.

- Page design and style are defined in the `style.css` file.
- Page animations and background effects are provided through the `particles.js` and `script.js` files.

This guide should help you understand the basic structure and usage of the page. Feel free to modify the content or customize the HTML and CSS files to suit your needs.

---

### Tips for Customization

1. **Updating Content:**
   - Modify the text in the `<h1>`, `<h3>`, and `<p>` tags to update your personal and professional information.
   - Change the `href` attribute in the `<a>` tag to update the email address in the "Contact Me" link.

2. **Adding/Removing Features:**
   - Duplicate or remove the feature cards in the "Features" section by replicating or deleting the corresponding HTML blocks.

3. **Custom Styling:**
   - Explore the `style.css` file to customize colors, fonts, and other styling elements.
   - Adjust the particle effects and animations in the `script.js` file for a personalized touch.

4. **Adding Images:**
   - Replace the `src` attribute in the `<img>` tag within the "About Me" section with the path to your own image.
   - Customize the image size and styling in the `style.css` file if needed.

5. **JavaScript Functionality:**
   - If you need to customize the scroll-to-top functionality, you can modify the `scrollToTop()` function in the `script.js` file.

---

### Important Reminders

- Make sure to keep backups of your original files before making significant changes.
- Test your webpage on different browsers to ensure compatibility.
- Regularly update your content to keep your webpage relevant.

---

Now you're ready to personalize and deploy your own version of the "Harun Yahya Aydın" web page. Happy coding!
