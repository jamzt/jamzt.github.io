/***** GENERAL STYLING *****/

/*Affects entire document */
html {
    scroll-behavior: smooth; /*This ensures that the page scrolling is smooth when the buttons on the nav bar is clicked */
}

/* Body */
body {
    margin: 0%; /* This ensures our site displays all the way to the edge of the browser screen */
    opacity: 1; /* This and transition affect the page loading fade in effect */
    transition: 3s opacity; /* This causes a 3 second fade in */
    letter-spacing: .2vw; /* vw is a relative measurement, 1vw is equal to 1% of the viewport width */
    font-family: Avant Garde, Helvetica;
    font-size: 1.5vw; 
    overflow-x: hidden; /* This prevents the horizontal scroll bar from appearing when the quote is hovered over */
    user-select: none; /* This prevents the text on the webpage from being highlighted by the user */
}

/* This section contributes to the fade effect for the page that occurs when the page is loaded */
body.fade-out {
    opacity: .1; /* This sets the level of opacity at the start of page load */
}

/* Heading 1 elements */
h1 {
    text-transform: uppercase; /*capitalizing all h1 headings */
    font-family: "Trebuchet MS", Optima; /* Sets the font family of all h1 headings */
    text-align: center; /* Centering all h1 elements */
    margin-top: 3%; /* Adds a small margin above h1 elements */
    color: #1a1a1a; 
}

/* Heading 1 element hover effect */
h1:hover {
    filter: grayscale(5%); /* Adds a slightly gray filter to the h1 headings when hovered over */
    transform: scale(1.1); /* When the h1 elements are hovered over they increase in size by 1.1 */
    transition: transform 1s; /* This causes the transformation to last 1 second */
}

/* Styling for Portfolio Title Text */
.white-text {
    color: #fff;/* This is used to change the color of the Portfolio Title text */
    padding-top: 10vh; /* Adds padding (equal to 10% of the viewport height) to the top of the Portfolio Title text */
}

/* Paragraph elements */
p {
    font-family: Perpetua, Rockwell Extra Bold;
    text-align: justify; /* This justifies the text within paragraph elements */
    letter-spacing: .1vw; /* This expands the text slightly */
    font-size: 2.5vw; /* Relative font sizing equal to 2.5% of the viewport width */
    padding-left: 1vw; /* Relative padding equal to 1% of the viewport width */
    padding-right: 1vw; /* Relative padding equal to 1% of the viewport width */
}

/* Paragraph element hover effect */
p:hover {
    transition: transform 1s; /* This makes the transform effect last 1 second */
	transform: scale(1.01); /* This makes the paragraphs increase slightly in size when hovered over */
}

/* Center class - this applies to all centered text */
.center {
    text-align: center; /* This center aligns the text */
}

/* Center align elements hover effect - This only affects the quote, github link, and footer */
.center:hover {
    transition: transform 2s; /* This makes the transform effect last 2 seconds */
    transform: scale(1.1); /* This makes the elements with class "center" increase in size by 1.1 when hovered over */
}

/* Anchor elements */
a {
    color: blue; /* This ensures all links are blue */
    cursor: pointer; /* This ensures all links change the mouse to a pointer when hovered over or clicked */
    text-decoration: underline; /* This ensures all links are underlined */
}

/* Quotation elements */
q {
    font-style: italic; /* Makes the quote italicized */
}

/* Image elements */
img {
    filter: grayscale(75%); /* This rids our pictures of 75% of their color */
    border-radius: 8px; /* Gives all images slightly rounded corners */
    max-width: 100%; /* Ensures all images stay within the width of their container */
    max-height: 100%; /* Ensures all images stay within the height of their container */
    display: block; /* By specifying block display we can ensure our images are able to be centered */
    margin: auto auto auto auto; /* This centers all images */
}

/* Image element hover effects */
img:hover {
	filter: grayscale(5%);  /* Brings back most of the image's color when hovered over */
}

/*Styling for footer element */
footer {
    padding: 2%; /* This gives the footer padding that is equal to 2% of the width of the element's area */
    background-color: white;
}
/***** End of General Styling *****/

/***** Navbar Styling *****/
.Navbar {
    overflow: hidden; /* This ensures that any content that overflows beyond the boundary of our nav bar is not displayed */
    background-color: black; /* This colors the navbar black */
    position: fixed; /* This keeps the navbar at the top of the screen as we scroll */
    top: 0; /* This ensures no space is displayed above the navbar */
    width: 100%; /* This makes the navbar span the entire width of the page */
    z-index: 1; /* This ensures other elements don't display over the navbar */
    -webkit-animation: moveNav 5s; /* Safari 4.0 - 8.0 */
    animation: moveNav 5s; /* This makes the moveNav animation last 5 seconds */
}

/* The animation effect for moving the nav bar in from above the left of the screen on page load */
@keyframes moveNav {
    from {left: -100vw;} /* The navbar is starting off screen to the left */
    to { left: 0vw;} /* This moves the navbar into place on the screen */
}

/*Navbar Links */
.Navbar a {
    float: left; /* This specifies that the text floats on the left on the navbar */
    display: block; /* This ensures that other text will be displayed on the same line or row, instead of a new line */
    color: white; /* This is the font color for text on our navbar */
    padding: .75vw 1vw; /* This adds padding around our text */
    text-decoration: none; /* This gets rid of the underlines under the text on our navbar */
    font-family: Avant Garde, Helvetica; /* This specifies the font family for text on our navbar */
    font-size: 1.5vw; /* This specifies the font size for text on our navbar */
    text-align: center; /* This centers the text within its container */
    position: relative; /* This sets the text relative to its normal positioning, allowing us to use the animation below */
    -webkit-animation: moveNavText 5.75s; /* Animation for Safari 4.0 - 8.0 */
    animation: moveNavText 5.75s; /* Applies the moveNavText animation for 5.75s */ 
}

/* The animation effect for moving the nav bar links in from above the top of the screen on page load */
@keyframes moveNavText {
    from {top: -100vw;} /* This sets the navbar text 100% above the viewport */
    to {top: 0vw;} /* This lowers the navbar text onto the navbar */
}

/*Navbar hover effects */
.Navbar a:hover {
    background-color: #f4f4f4; /* Defines the background color that will display when you hover over the link */
    color: black; /* This defines the font color that will display when navbar a elements are hovered over */
    font-weight: bold; /* This makes the text on the navbar bold when hovered over */
    cursor: pointer;
    transition: 0.5s ease-in; /* Creates a smooth transition for the hover trigger */
}

/* Navbar home button */
.Navbar a.active { /* This targets the a element on the navbar with the "active" class */
    background-color: darkgray;
}
/***** End of Navbar Styling *****/

/***** Video Styling *****/
/* Formatting for background video */
#Typing_Video {
    position: fixed; /* This fixes the video to the page */
    right: 0; /* This ensures there is no space between the edge of the video and the edge of the page */
    bottom: 0; /* This ensures no space between the edge of the video and the bottom of the page */
    min-width: 100%; /* This ensures the video is displayed across the full width of the page */
    z-index: -1; /* This places the video behind the other elements on the page */
}

/* Screens that are 576px and smaller will not display the background video */
@media screen and (max-width: 576px) {
    #Typing_Video {
        display: none;
    }
}

/* Texts over the video */
.Video_Text {
    background: rgba(0, 0, 0, 0.5); /* This provides a semi-transparents background for the text to sit over */
    color: white; /* Makes the font color white */
    width: 100%; /* Ensures the video-text container fills the width of the video */
    height: 100vh; /* This ensures the video-text container fills the height of the viewport so that the slideshow is not partially displayed */
    padding-top: 2vh; /* This adds padding around the video-text container so that the background goes slightly beyond the text */
    position: relative; /* This sets the text relative to its normal positioning, allowing us to use the animation below */
    -webkit-animation: moveVideoText 5.75s; /* Animation for Safari 4.0 - 8.0 */
    animation: moveVideoText 5.75s; /* moveVideoText animation set to 5.75s to match the movenavText animation */
}

/* This animation effect causes the overlay video text to move up from the bottom of the page upon page load */
@keyframes moveVideoText {
    from {top: -100vw;} /* This sets the position of the video text to above the viewport */
    to {top: 0vw;} /* This moves the video text to the normal positioning on the viewport */
}
/***** End of Video Styling *****/

/***** Slideshow Styling *****/
#Slideshow_Background {
    background: rgba(255, 255, 255, 0.35); /* This creates a slightly transparent white background that's palced over the video in the background */    
}

.mySlides{
    display: none; /* This prevents the images from being displayed, we will use JS to display these */
}

/* Slideshow section / container */
#Slideshow_Container {
    width: 39.5vw; /* Relative sizing of the container for the slidewshow set to 39.5% of the viewport width */
    height: auto; /* The height of the container is automatically adjusted based on the content it is displaying */
    padding-top: 4%; /* Adds a small padding to the top of the slideshow container */
    position: relative; /* This sets the container relative to its normal positioning */
    margin:auto; /* This will horizontally center the container on the page */
}

/* Remove the underline from the previous and next buttons on the slideshow */
#Slideshow_Container a {
    text-decoration: none;
}

/* Images contained within the slideshow */
.Slideshow_Images {
    vertical-align: middle; /* This centers the images vertically within the slideshow container */
    height: auto; /* The height of the images is automatically adjusted based on the content, ie if your images are different sizes, they will display as different sizes */
    box-shadow: 0px 5px 10px 12px rgba(0, 0, 0, .75); /* Adds a shadow around the slideshow images */
    width: 100%; /* The width of the images is automatically adjusted based on the content */
}

/* Next and previous buttons */
.Previous, .Next {
    cursor: pointer; /* Changes the mouse to a pointer when the buttons are selected */
    position: absolute; /* This makes the next and previous buttons positioned relative to the slideshow container */
    top: 50%; /* This moves the buttons up in the slideshow container */
    width: auto; /* The width of the buttons is automatically adjusted based on the content */
    padding: 2vw; /* Adds padding equal to 2% of the viewport width */
    color: darkgray; 
    font-weight: bold;
    font-size: 1.5vw;
    border-radius: 0 3px 3px 0; /* Adds a slightly rounded border on the top and bottom right corners */
    user-select: none; /* This property makes it so that the user cannot highlight the text */
    transition: 0.6s ease; /* This specifies the details of the hover transition for these elements */
}

/* Positioning the next button on the right hand side */
.Next {
    right: 0; /* This moves the next button to the right side of the slideshow container */
    border-radius: 3px 0 0 3px; /* This changes the border radius on the next button to the top and bottom left of the button */
}

/* Hover effect on slide show buttons */
.Previous:hover, .Next:hover {
    background-color: rgba(0, 0, 0, 0.8); /* Makes the background of the arrows a transparent gray color */
    color: white; /* Makes the arrows white when hovered over */
}

/* Slideshow text */
.text {
    color: white; 
    padding: 1vw;
    position: absolute; /* This ensures the text is positioned within the image */
    bottom: 0; /* This property sets the text at the bottom of the image */
    width: 100%; /* The element covers the full width of the image */
    text-align: center; /* The text is center aligned within the image */
    font-family: Perpetua, Rockwell Extra Bold;
    letter-spacing: .1vw; /* This gives slight spacing between the letters */
    font-size: 1.5vw; /* Font size is relative to the size of the viewport width */
    background-color: rgba(0, 0, 0, 0.75); /* Gives a slightly transparent black background */
    font-weight: bold;
    border-radius: 0px 0px 7px 7px; /* Gives the text background rounded corners on the bottom left and right corners */
}

/* Styling of the dots under the slideshow */
.dot {
    cursor: pointer; /* The cursor changes to pointer when hovered over the dots */
    height: 1vw; /* The dots are sized relative to the viewport width */
    width: 1vw;
    margin: .25vw; /* adds additional spacing between the dots */ 
    background-color: white; /* Makes the dots white */
    border-radius: 50%; /* Makes the dots circles by rounding each corner */
    display: inline-block; /* Allows the dots to sit next to eachother rather than on a new line */
    transition: background-color 0.6s ease; /* When clicked on the dots transition to a different color when clicked or hovered over (the affect is defined below) */
    z-index: 1; /* This ensures the dots will be displayed above any other elements */
}

/* Hover effect for slideshow dots */
.active, .dot:hover {
    background-color: black; /* Sets the color of the dots when active or hovered over */
}

/* Fading animation for slideshow */
.fade {
    animation-name: fade; /* Fade animation is defined below */
    animation-duration: 1.5s; /* The animation lasts 1.5 seconds */
    -webkit-animation-name: fade; /* Same as above for Safari 4.0-8.0 */
    -webkit-animation-duration: 1.5s;
}

@-webkit-keyframes fade {
    from {opacity: .4;} /* Image starts transparent */
    to {opacity: 1;} /* Image ends opaque */
}

@keyframes fade {
    from {opacity: .4;} /* Image starts transparent */
    to {opacity: 1;} /* Image ends opaque */
}
/***** End Slideshow Styling *****/

/***** Table Styling -  this section covers the styling of the columns and rows within the table *****/
* { /*The asterisk is a universal selector that applies this effect to all elements on the page */
    box-sizing: border-box; /* This creates a box with a border within which we will place most of our text */
} 

.Column_1 {
    float: left;
    width: 50%; /* This ensures the column takes up half of the page width */
    padding: 1.6%;
    height: 450px; /* This sets the height of the column to 400px -  this may need to be adjusted depending on the text you enter */
    background-color: #f2f2f2; /* Sets the background color of the left columns */
}

.Column_2 {
    float: left;
    width: 50%;
    padding: 1.6%;
    height: 450px;
    background-color: #4d4d4d;
}

/* This inserts something after the content of selected elements (in this case the elements with class "Row") */
.Row:after {
	content: ""; /* By leaving this blank, we are allowing the footer (covered lower down) to be displayed - removing it makes the footer overwrite a column */
	display: table; /* The display property specifies the type of display behavior; the table value tells the browser to treat the element as a table */
	clear: both; /* This clears any other elements from floating on the left or the right of an element */
}
/***** End of Table Styling *****/

/***** Contact Form Styling *****/
/* Button used to open the contact form - fixed at the bottom of the page */
.Pop_Up_Button {
    position: fixed; /* The element is positioned relative to the viewport and stays in the same location no matter what */
    bottom: 1.75vw; /* Positions the button slightly up from the bottom of the viewport */
    right: 1.75vw; /* Positions the viewport slightly right from the side of the viewport */
    width: 25vw; /* Sets the width relative to the viewport width */
    background-color: white; /* Sets the background color of the button to white */
    color: black; /* Sets the color of the button text to black */
    border: solid black; /* This makes a solid black border around the button */
    cursor: pointer; /* This changes the cursor when hovered over the button to a pointer */
    -webkit-animation: movePopup 5s; /* Animation for 5 seconds for Safari 4.0-8.0 */
    animation: movePopup 5s; /* Animation set for 5 seconds */
}

/* movePopup animation moves the button from off the right side of the screen to its fixed location on the viewport */
@keyframes movePopup {
    from {right: -40vw;} 
    to {right: 1.75vw;}
}

@-webkit-keyframes movePopup {
    from {right: -40vw;} 
    to {right: 1.75vw;}
}

/* Styling for the contact form */
.form-popup {
    z-index: 8; /* This z-index ensures the contact form shows above all other elements on the page */
    display: none; /* Set the display to none, we will use JavaScript to show the contact form */
    position: fixed; /* The form stays in the same location no matter what */
    bottom: .5vw; /* Slightly up from the bottom of the viewport */
    right: .5vw; /* Slightly in from the right side of the viewport */
}

/* Form styling */
.form-container {
    max-width: 49vw; /* Relative sizing of the form container - 49% of the viewport width */
    padding: 1vw; /* Adds padding between the form-popup and the form-container */
    background-color: white; 
}

/* Input fields */
.form-container input[type=text] {
    width: 100%; /* The input boxes completely fill the width of the form-container */
    padding: .93vw; /* Adds padding to the input boxes */
    margin: .6vw 0 .6vw 0; /* Adds space between the input boxes and the labels */
    border: none; /* Removes the border from the input boxes */
    background: Gainsboro; /* Sets the background color of the input boxes */
    font-size: 1vw; /* Relative font sizing based on the width of the viewport */
}

/* General styling for all buttons */
button {
    font-family: "Trebuchet MS", Optima;
    letter-spacing: .3vw; /* Adds slight spacing between the letters */
    font-size: 1.5vw; /* Relative sizing of text */
    font-weight: bold; 
    padding: 1.5vw; /* Adds padding to the text in the button */
    cursor: pointer; /* Changes the cursor to pointer over button elements */
    width: 100%; /* Sets the width of the buttons to 100% of their containers */
    height: auto; /* Allows the height to be resized depending on the content showing */
}

/* Hover effect for contact and submit buttons */
button:hover, .form-container .btn:hover {
    color: white; /* This makes the text in the buttons white when hovered over */
    background-color: black; /* The background of the button changes to black when hovered over */
    transition-duration: 1s; /* This makes the transition last 1 second */
    -webkit-transition-duration: 1s; /* For Safari 4.0-8.0 */
    border-color: silver; /* The border turns silver when the button is hovered over */
}

/* Submit button */
.form-container .btn {
    background-color: white; 
    color: black;
    border-color: black;
    margin-bottom: 1vh; /* Adds space between the submit button and the close button */
}

/* Close button */
.form-container .cancel {
    background-color: black;
    color: white;
    border-color: gray;
}

/* Styling for close button on hover */
.form-container .cancel:hover {
    color: white;
    background-color: darkred;
    transition-duration: 1s;
    -webkit-transition-duration: 1s;
    border-color: black;
}
/***** End of Contact Form Styling *****/

/***** Media Query Section *****/
/*Media rules for paragraph font size for different screen sizes*/
@media screen and (max-width: 527px) {
    p {
        font-size: 3.75vw;
    }
}

@media screen and (min-width: 528px) and (max-width: 660px) {
    p {
        font-size: 3.5vw;
    }
}

@media screen and (min-width: 661px) and (max-width: 799px) {
    p {
        font-size: 2.75vw;
    }
}

@media screen and (min-width: 800px) and (max-width: 924px) {
    p {
        font-size: 2.5vw;
    }
}

@media screen and (min-width: 925px) and (max-width: 1050px) {
    p {
        font-size: 2.25vw;
    }
}

@media screen and (min-width: 1051px) and (max-width: 1310px) {
    p {
        font-size: 2vw;
    } 
}

@media screen and (min-width: 1311px) and (max-width: 1535px) {
    p {
        font-size: 1.75vw;
    }
}

@media screen and (min-width: 1536px) and (max-width: 2269px) {
    p {
        font-size: 1.5vw;
    }
}

@media screen and (min-width: 2270px) {
    p {
        font-size: 1.35vw;
    }
}

/*Media rule for navbar links for different screen sizes*/
/* Screens 1080px and smaller will display navbar links equally distributed */
@media screen and (max-width: 1080px) {
    .Navbar a{
        width: 20%; /* This sets each navbar link to 1/5 of the navbar */
        font-size: 2.5vw;
    }
}

/* Media rules to enlarge the font of the white text for smaller screens */
@media screen and (max-width: 1080px) {
    .quote{
        font-size: 3.5vw;
    }

    .white-text {
        font-size: 4.5vw;
    }
}

/* Media rules to increase the size of the columns for larger screens */
@media screen and (min-width: 1725px) {
    .Column_1 {
        height: 550px;
    }
    .Column_2 {
        height: 550px;
    }
}


/*Media rule to remove margin-top from h1 elements for extra large screens (so that the paragraph text fits in the column*/
@media screen and (min-width: 2000px) {
    h1{
        margin-top: 0;
    }
}
/***** End of Media Query Section *****/