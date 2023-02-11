# Bouncing_square_.github.io

This is a solid square created using CSS Styling jumping over a trampoline also created using CSS styling

The HTML Class structure being used here is :-

  <div class="container">
        <div class="wrapper">
            <div class="rubber">
            </div>
            <div class="stick left-stick"></div>
            <div class="stick right-stick"></div>
            <div class="square"></div>
        </div>
  </div>

 - The "Container" div being used here wncapsulates the complete screen and give platform for other divs (child elements)
 - The "wrapper" div class being used encapsuates the sware and trampoline structure (the content at the center of screen).
 
 **Read below description only when want to know in dept about styling used**
 
The  CSS code creates an animated bouncing square in an HTML file. Here is a step by step explanation of the code:

 - The first block of code is the HTML file header that sets the character encoding, sets the document type and provides some metadata. The title of the page is set as "Jumping Square" and a stylesheet "Bouncing_square_style.css" is linked to the HTML file.

 - In the next block, the body of the HTML file contains a div with class "container". This is the main container for the animation and it is set to take up 100% of the view height and width of the screen. It is also set to display as a grid and center-aligned.

 - Inside the "container" div, there is another div with class "wrapper". This div sets the width, height, background color, border radius, and box shadow of the container for the animation. It is set to be relative in position and has its overflow set to hidden.

 - In the "wrapper" div, there are four other divs with classes "rubber", "stick", "left-stick", and "square". These divs represent different parts of the bouncing square animation.

 - The "rubber" class sets the width, height, border, and box shadow of the bottom part of the animation. It also has an animation named "rubberanim" that runs continuously with a duration of 2 seconds.

 - The "stick" class sets the width, height, background color, and border radius of the two sticks on either side of the animation.

 - The "left-stick" class is applied to one of the "stick" divs and sets its position to the left side of the animation. It also has an animation named "leftstickanim" that runs continuously with a duration of 2 seconds.

 - The "right-stick" class is applied to the other "stick" div and sets its position to the right side of the animation. It also has an animation named "rightstickanim" that runs continuously with a duration of 2 seconds.

 - The "square" class sets the width, aspect ratio, background color, border radius, and box shadow of the square in the animation. It also has an animation named "squareanim" that runs continuously with a duration of 2 seconds.

 - Finally, the code contains several keyframes for each of the animations. These keyframes specify the transformation that occurs at various points in time during the animation.

**In conclusion, this code creates an animated bouncing square by using CSS animations and keyframes. It creates a container and sets its properties, creates different parts of the animation using divs and sets their properties, and finally creates animations for each part of the animation using keyframes.
