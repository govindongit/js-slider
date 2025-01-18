# Image Slider

This project demonstrates how to create a simple image slider using HTML, CSS, and JavaScript.

## JavaScript Concepts Used in the Image Slider

### 1. JavaScript Fundamentals:
- **Variables and Constants**: 
  - Declaration of variables such as `sliderImages`, `arrowLeft`, `arrowRight`, and `current` to store references to DOM elements and the current slide index.
  
- **Functions**: 
  - Modular functions like `reset()`, `startSlide()`, `slideLeft()`, and `slideRight()` are defined to organize the code, promote reusability, and separate concerns.
  
- **Event Handling**: 
  - Utilization of `addEventListener()` to handle user interaction with the arrows, triggering changes to the slide display on click events.

- **Conditional Statements**: 
  - `if` statements control the behavior of the slider, such as checking if the user has reached the first or last slide to loop through the slides.

- **DOM Manipulation**: 
  - DOM elements are selected and manipulated with methods like `document.querySelectorAll()` and by directly modifying the `style.display` property to dynamically show or hide elements.

### 2. DOM Selection and Manipulation:
- **Querying the DOM**: 
  - `querySelectorAll()` and `querySelector()` are used to access and store multiple or individual DOM elements (e.g., the slider images and arrow buttons).
  
- **Manipulating Styles**: 
  - The `style` property is used to dynamically change the visibility of elements (e.g., `sliderImages[i].style.display = "none";`) based on user interactions.

### 3. Event Listeners and User Interaction:
- **User Interaction**: 
  - Click event listeners are added to the arrow elements, which, upon user click, trigger the logic to update and display the next or previous slide.

- **Navigating Slides**: 
  - The slider functionality is controlled by "next" and "previous" logic, which is implemented to change the displayed slide in response to arrow clicks.

### 4. Arrays and Loops:
- **Arrays (or NodeLists)**: 
  - `sliderImages` holds multiple DOM elements as an array-like structure (NodeList), and these elements are dynamically accessed and modified.
  
- **For Loops**: 
  - A `for` loop is used to iterate over the elements in `sliderImages` (e.g., to hide all slides in the `reset()` function before showing the active slide).

### 5. JavaScript Logic for Image Slider:
- **Slide Control Logic**: 
  - The slider logic ensures that only one slide is displayed at a time, with the `current` index used to track which image is currently visible.

- **Edge Case Handling**: 
  - When the user clicks the left or right arrows at the edges of the slider (first or last slide), the logic is in place to loop back to the opposite end (e.g., the first slide if currently on the last one, and vice versa).

---

## How to Use

1. Clone the repository.
2. Open `index.html` in your browser.
3. Click the arrows to navigate through the slides.
4. Enjoy the smooth image transition!

---

## Technologies Used

- **HTML**: Structure of the image slider.
- **CSS**: Styling the slides and the arrows.
- **JavaScript**: Functionality for slide transitions and event handling.

---

---

## Acknowledgements

This project was inspired and built with the help of resources from [GeeksforGeeks (GFG)](https://www.geeksforgeeks.org/).

---

## License

This project is open source and available under the [MIT License](LICENSE).
