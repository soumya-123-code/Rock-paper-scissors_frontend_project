# Rock Paper Scissors

## Experience the classic game of Rock Paper Scissors in a sleek and interactive online format. Play against the computer and test your luck!

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)
- [Got Feedback for Me?](#got-feedback-for-me)

## Overview

### The Challenge

Experience the classic game of Rock Paper Scissors in a sleek and interactive online format. Play against the computer and test your luck!

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Design Preview](./design/desktop-preview.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/soumya-123-code/Rock-paper-scissors_frontend_project)
- Live Site URL: [Live Site](https://rock-paper-scissors-frontend.netlify.app/)

## My Process

### Built With

- HTML5
- CSS3
- JavaScript

You will find all the required assets in the `/design` folder. The assets are already optimized.

There is also a `style-guide.md` file containing the information you'll need, such as color palette and fonts.

### What I Learned

- Implementing game logic for Rock Paper Scissors in JavaScript
- Styling and animating elements for an engaging user experience
- Handling user input and computer-generated choices for gameplay

This given code snippet took me a lot of time to implement due to the complexity of this design and thus really helped me out in clearing my CSS concepts to the next level.

```css
.game-body__circle-container-paper{
    position: absolute;
    left: 0;
    top: -6.5rem;
}
.game-body__circle-container-scissors{
    position: absolute;
    right: 0;
    top: -6.5rem;
}
.game-body__circle-container-rock{
    position: absolute;
    left: 50%;
    bottom: 6rem;
    transform: translateX(-50%);
}
.game-body__circle-container-paper,
.game-body__circle-container-scissors,
.game-body__circle-container-rock{
    transition: all 0.5s ease-in-out;
}
.game-body__big-circle{
    width: 13rem;
    height: 13rem;
    border-radius: 50%;
    overflow: hidden;
    position: relative;
    box-shadow: 0 3px 3px rgb(0 0 0 / 25%);
}
.game-body__big-circle--dark-blue{
    background-color: #2642bf;
}
.game-body__big-circle--dark-yellow{
    background-color: #c76b18;
}
.game-body__big-circle--dark-red{
    background-color: #9d1736;
}
.game-body__big-circle--light-blue,
.game-body__big-circle--light-yellow,
.game-body__big-circle--light-red{
    transform: translateY(-6px) scale(1.03);
}
.game-body__big-circle--light-blue{
    background-image: linear-gradient(120deg, hsl(230, 89%, 62%), hsl(230, 89%, 65%));
}
.game-body__big-circle--light-yellow{
    background-image: linear-gradient(120deg, hsl(39, 89%, 49%), hsl(40, 84%, 53%));
}
.game-body__big-circle--light-red{
    background-image: linear-gradient(120deg, hsl(349, 71%, 52%), hsl(349, 70%, 56%));
}
.game-body__tiny-circle{
    width: 10rem;
    height: 10rem;
    border-radius: 50%;
}
.game-body__tiny-circle--dark-white{
    background-color: #bfbfbf;
    overflow: hidden;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
}
.game-body__tiny-circle--light-white{
    background-color: #ddd;
    transform: translateY(4px) scale(1.02);
}
```

### Continued Development

The continuously learning journey of a programmer never ends. This project made me realize that there are many concepts that I need to work upon including fundamentals like flex-box and its properties, to more complex concepts like working with fetch and async await in JavaScript. These areas are some that I think I need to work more upon in the upcoming future as they highlight some of the most significant regions of web development that are important for every developer to know of.

These key points mentioned here will help me grow accountable and consistent towards improving at writing good quality code and becoming a successful full stack developer one day.

### Useful Resources

- [MDN documentation hover state for CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover) - This is an amazing article that helped me finally understand hover states. I'd recommend it to anyone still learning this concept.

## Author

<b><strong>Soumya Ranjan Nayak</strong></b>
- Website - [Soumya Ranjan Nayak](https://soumya-123-code.github.io/itsmesoumya)
- GitHub - [@soumya-123-code](https://github.com/soumya-123-code/)
- LinkedIn - [Soumya Ranjan Nayak](www.linkedin.com/in/soumya-ranjan-nayak-50069a15a)

## Acknowledgments

I appreciate all the support from the open-source community and various online platforms that help developers grow by suggesting best practices in their respective tech stacks.

## Got Feedback for Me?

I love receiving feedback! I am always looking to improve my code and take up new innovative ideas to work upon. So if you have anything you'd like to mention, please email 'hi' at soumya050794@gmail.com.

If you liked this project, make sure to spread the word and share it with your friends.

**Happy coding!** ☺️🚀

