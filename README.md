student name:atungdiwe asinah
student number:041140443

Assignment 3

## What I did

I built a prototype for my NASA APOD web app using HTML and Tailwind CSS. The goal was to make sure the user flow actually felt smooth moving from picking a date to seeing the "Pillars of Creation" result. I kept it all on one page to make it feel more like a modern app.

## Resources

- **Tailwind CSS**: Used this for almost all the styling because I wanted to learn how utility classes work.
- **Google Fonts**: To get that clean, modern look for the "Cosmos" heading.
- **Unsplash**: Grabbed a high-quality space photo for the results mockup.

## Challenges & Fixes

- **Installing Tailwind**: i watched videos to install tailwind and i I tried to use the terminal/npx method, but it kept giving me errors like "npx is not recognized." Instead of wasting hours on that, I switched to the Play CDN method so I could actually focus on the design. I still kept my `style.css` file for the custom animations.
- **The Navigation Bug**: One of the main challenges was making the "Home" button actually work. At first, after you found a picture, you were just stuck there. I had to write a JavaScript function to reset the visibility of the sections. Now, when you tap the rocket or the "Home" button in the nav, it hides the results and brings the search section back so you can pick a new date.
- **Responsiveness**: Getting the search card to stay centered and look good on my phone was tricky, but Tailwind's `flex` and `md:` classes made it way easier.

## How to Test

1. Open `index.html`.
2. Pick a date and hit "Explore."
3. Once the image shows up, click "the refrest button" in the top bar to see it reset back to the search screen.
