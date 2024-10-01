# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

> 💡 These are just the design sizes. Ensure content is responsive and meets WCAG requirements by testing the full range of screen sizes from 320px to large screens.

## Colors

### Primary

- Green: hsl(75, 94%, 57%)

### Neutral

- White: hsl(0, 0%, 100%)
- Grey: hsl(0, 0%, 20%)
- Dark Grey: hsl(0, 0%, 12%)
- Off Black: hsl(0, 0%, 8%)

## Typography

### Body Copy

- Font size (paragraph): 14px

### Font

- Family: [Inter](https://fonts.google.com/specimen/Inter)
- Weights: 400, 600, 700

> 💎 [Upgrade to Pro](https://www.frontendmentor.io/pro?ref=style-guide) for design file access to see all design details and get hands-on experience using a professional workflow with tools like Figma.

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->
    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./assets/images/favicon-32x32.png"
    />

    <title>Frontend Mentor | Social links profile</title>
    <link rel="stylesheet" href="styles/index.css" />
    <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
    <style>
      .attribution {
        font-size: 11px;
        color: hsl(0, 0%, 100%);
        text-align: center;
        margin-top: 20px;
      }
      .attribution a {
        color: hsl(228, 45%, 44%);
      }
    </style>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap"
      rel="stylesheet"
    />

  </head>
  <body class="body">
    <main class="main">
      <div class="container">
        <img
          src="assets/images/avatar-jessica.jpeg"
          alt="avatar-jessica"
          class="avatar"
        />
        <h1 class="name">Jessica Randall</h1>
        <p class="address">London, United Kingdom</p>
        <p class="job">"Front-end developer and avid reader."</p>

        <a
          class="link button"
          href="https://github.com/ahmedabd2lkarim"
          target="_blank"
        >
          GitHub
        </a>
        <a
          class="link button"
          href="https://www.frontendmentor.io/"
          target="_blank"
        >
          Frontend Mentor
        </a>
        <a
          href="https://www.linkedin.com/in/ahmed-abd-el-karim-1b12252a6/"
          target="_blank"
          class="link button"
        >
          LinkedIn
        </a>
        <a href="https://www.x.com" target="_blank" class="link button">
          Twitter
        </a>
        <a href="https://www.instagram.com" target="_blank" class="link button">
          Instagram
        </a>
      </div>
    </main>
    <!-- <footer class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by <a href="#">Ahmed Abd El-Karim</a>.
    </footer>

  </body>
  </html>
  --></body>
</html>

:root {
--green-primary: hsl(75, 94%, 57%);
--white-neutral: hsl(0, 0%, 100%);
--grey-neutral: hsl(0, 0%, 20%);
--dark-grey-neutral: hsl(0, 0%, 12%);
--Off-black-neutral: hsl(0, 0%, 8%);
}

.body {
background-color: var(--Off-black-neutral);
font-family: "inter", sans-serif;
max-width: 1440px;
margin: 0;
}

.main {
position: relative;
/_ width: 100%; _/
/_ display: flex;
align-items: center;
justify-content: center;
/_ height: 100vh; _/
/_ display: table;
vertical-align: middle; _/
/_ align-items: center;
justify-content: center; _/
}
.container {
width: 100%;
max-width: 250px;
background-color: var(--dark-grey-neutral);
/_ display: table;
vertical-align: middle; _/
/_ flex-flow: nowrap column;
align-items: center;
justify-content: center; _/
/_ padding: 100px 30px; \*/
border-radius: 2%;
position: absolute;
top: 50%;
left: 50%;
margin-left: ;

margin: auto;
/_ height: 50vh; _/
}
.avatar {
width: 68px;
border-radius: 100%;
}

.name {
color: var(--white-neutral);
font-weight: 700;
margin-bottom: 10px;
font-size: 24px;
}

.address {
color: var(--green-primary);
font-size: 14px;
font-weight: 600;
margin-top: 0;
}

.job {
font-size: 12px;
font-weight: 400;
color: var(--white-neutral);
}

.button {
background-color: var(--grey-neutral);
border: var(--dark-grey-neutral);
color: var(--white-neutral);
width: 250px;
height: 40px;
border-radius: 8px 8px;
font-weight: 700;
margin-bottom: 10px;
text-decoration: none;
text-align: center;
line-height: 40px;
font-size: 12px;
font-family: "inter", sans-serif;
}

.button:hover {
cursor: pointer;
color: var(--Off-black-neutral);
background-color: var(--green-primary);
border: none;
}

.info {
text-decoration: none;
font-style: normal;
color: var(--white-neutral);
}
/_
.attribution {
position: absolute;
left: 50%;
} _/

@media (max-width: 375px) {
.body {
width: 375px;
height: 812px;
margin: auto 0;
}
}
