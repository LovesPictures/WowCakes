# Cakes Co

Made to create a **responsive webpage** showcasing your cake business, based on two provided wireframes.

## Wireframes

Build the mobile wireframe first, then adapt it for larger screens.

_Mobile wireframe:_  
![alt text](./design/cakes%20wireframe%20-%20mobile.png "Cakes Co mobile design")

_Desktop wireframe:_  
![alt text](./design/cakes%20wireframe%20-%20desktop.png "Cakes Co desktop design")

## Approach

Make a template for the three screen scenarios
Template 

![alt text](https://github.com/LovesPictures/WowCakes/blob/master/img/Slide6.JPG "twireframe template")
https://github.com/LovesPictures/WowCakes/blob/4d2139c334692438dcca671bda7c780e79b64417/img/Slide6.JPG

### Define your own style

- Choose 1-2 fonts to use (lots of [free fonts here](https://fonts.google.com/))
- Choose 2-3 colours that you think go together well, and try to limit yourself to those in your CSS ([look here](https://coolors.co/palettes/trending) for inspiration)
- Select some nice cake pictures to replace the placeholders in the wireframes (good [photo source here](https://unsplash.com/images/food/cake)).

### mobile first

- Page desinged with a mobile first design approach
- Then write your CSS for everything to look great on mobile

### larger screens

- Following the mobile fist apprache the page was adjusted with media queries larger screen layouts and sizing of elements so they make better use of a wider screen

### breakpoints

> - breakpoint 1 --> 700px
> - breakpoint 2 --> 701px

Then our CSS code will be split into **3**:

> 1. **"default"**: default styles, should implement the mobile design (no media query used for these). These styles will apply to all screen sizes by default.
> 2. **"medium and large"**: The second media query `@media (min-width: 701px) with no upper limit

## Deployment (optional)

[Deploy your work to Netlify!](https://syllabus.codeyourfuture.io/workshops/deployment/workshop/instructions/)
Remember to follow this naming convention when creating your custom URL in Netlify: `https://cyf-[your-Github-username]-cakes.netlify.app/`
