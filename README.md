# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Screenshot

![Mobile screenshot](screenshots/mobile.png)

![Desktop screenshot](screenshots/desktop.png)


## Links

- [Solution URL](https://github.com/sebasmartinezchas/qr-code)
- [Live Site URL](https://sebasmartinezchas.github.io/qr-code)

## My Process

- The first thing I focused on was structuring and positioning the core layout elements. 
- Once the main structure was in place, I moved on to the finer details.


## Built with

- Semantic HTML5 markup
- Flexbox


## What I learned

- **Semantic HTML (`<main>` vs `<div>`):** I chose to use `<main>` instead of a generic `<div>` to improve accessibility and SEO, allowing screen readers and search engines to easily identify the primary content of the page.
- **Responsive Scaling (`min()`):** Using `min(100% - 2rem, 300px)` ensures the layout remains safe and readable on mobile devices by leaving a small margin, while preventing it from stretching past a clean, maximum width on larger desktop monitors.

```html
<main>Not everything needs to be a div</main>
```

```css
.container {
    width: min(100% - 2rem, 300px);
}
```

## Continued development

In .container I used margin: 250px auto to center the card, which causes problems on phones in landscape mode. This could be solved with CSS Grid, using its alignment properties so the layout adapts to the browser’s viewport instead of relying on a fixed margin. I’ll practice this in the next challenge.


## Author

- Andres Sebastian Martinez Chas
- Frontend Mentor - [@sebasmartinezchas](https://www.frontendmentor.io/profile/sebasmartinezchas)
