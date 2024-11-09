# CSS Positioning Exercise

## Project Description
This is a simple web page demonstrating CSS positioning properties using a blue box with a red circle inside it. The blue box is positioned absolutely, while the red circle inside the box is positioned relatively to showcase how different CSS `position` properties affect layout.

## Project Structure
- `index.html`: Contains the HTML structure.
- Inline CSS within the `<style>` tag defines the positioning and styling of the elements.

## Code Explanation
1. **Blue Box**:
   - Defined as a div with the class `blue-box`.
   - It has a fixed height and width (300px by 500px) and is styled with a blue background color.
   - Positioned using `position: absolute;` at 200px from the top and 200px from the left of the viewport.
   
2. **Red Circle**:
   - Defined as a div inside the `blue-box` with the class `red-circle`.
   - It has a fixed height and width (200px by 200px) and is styled with a red background color and circular shape (`border-radius: 50%`).
   - Positioned using `position: relative;` at 150px from the top and 250px from the left relative to its original position within the blue box.

## Setup
1. Save the code as `index.html`.
2. Open `index.html` in a web browser to see the blue box with a red circle positioned as per the CSS specifications.

## Notes
- **CSS Positioning**: This project demonstrates the use of `position: absolute;` and `position: relative;` CSS properties. The absolute positioning of the blue box is relative to the viewport, while the relative positioning of the red circle is in relation to its default position within the blue box.
- Experiment with the `top` and `left` values in CSS to see how the elements' positioning changes.
