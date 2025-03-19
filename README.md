# CSS3 Transitions, Animations, and Advanced JavaScript Functions

## Objectives

Create smooth CSS transitions and animations.
Use JavaScript functions for dynamic behavior.
Implement local storage for data persistence.

## Instructions
Add CSS animations to elements like buttons or images.

>[!NOTE]
> - Write a JavaScript function that:
> - Stores and retrieves user preferences using localStorage.
> - Implements an animation triggered by user actions.

## Tasks

Create a CSS animation.
Store data in localStorage.
Apply JavaScript to trigger animations.
```css
/* Define keyframes for a simple fade-in animation */
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

/* Apply the animation to a button */
button {
  animation: fadeIn 1s ease-in-out; /* Duration: 1 second, easing: ease-in-out */
}
```

For storing user preferences in localStorage, you'll use JavaScript's `localStorage` object. Here's how you can store and retrieve data:

```javascript
// Store user's preferred color
localStorage.setItem('userColor', 'blue');

// Retrieve the stored color
const userColor = localStorage.getItem('userColor');
```

Finally, to trigger animations using JavaScript, you can use event listeners. Here's how you can make a button animate when clicked:

```javascript
const button = document.querySelector('button');

button.addEventListener('click', () => {
  button.classList.add('animated'); // Add a class with your animation defined in CSS
});
```


Happy Coding! 💻✨
