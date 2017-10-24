# Tennis Tech Test

A brief explanation of my process creating blocks of content for the team at Tennis.

My coding process began, like it always does, without coding at all. Instead, I took the time to thoroughly analyze the finished product, taking note of patterns and consistencies that would help to establish more elegantly written code. I took the pdf into Adobe Creative Cloud, and established the base colours that would be used throughout the project, saving them as SASS variables for future editability. I also planned out the approach to typography, including sourcing the appropriate Google Font and measuring sizes and weights.

I wrote semantic markup with consistency and accessibility in mind, using the BEM naming convention where possible to keep my CSS flat and readable. Of course, in a real world application, the content of these cards would be populated dynamically based on an AJAX call and filters - my code allows for styles to stay consistent even with unknowns like these.

The cards themselves are responsive, resizing and styling themselves based on popular device widths. This reponsiveness was handled succinctly using a dedicated media query partial. To add a touch of feedback (and hopefully user delight), I added hover states (and an active state on the button) to have the cards react to user interaction.
