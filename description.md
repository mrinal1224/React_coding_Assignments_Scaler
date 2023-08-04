Create a star rating widget that allows users to select a rating value.

Requirements->

1.The widget accepts two parameters: the maximum number of stars and the number of currently filled stars.

2.When a star is clicked, it is filled along with all the stars to its left.

3.When the user hovers over the stars, all the stars under the cursor and its left are filled.

4.The stars which need to be filled during hover take priority over existing filled state.

5.If the cursor leaves the widget and no new selection is made, the appropriate stars revert to the filled state before the hovering.

6.Make the star rating widget reusable such that multiple instances can be rendered within the same page.
The star icons, both empty and filled, are provided to you as SVGs.

A StarRating.js skeleton component has been created for you. You are free to decide the props of <StarRating />.



Test Cases - 

1.Click on each star and move the cursor away, see that the highlighted state is correct.

2.Hover over each star, see that every star under the cursor and to its left are highlighted.

3.Remove cursor over widget, see that the highlighted state is back to before the hovering.

4.Render multiple components, ensure that each can maintain its own state and interacting with a widget does not affect other onscreen components.


