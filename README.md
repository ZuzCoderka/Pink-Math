# Pink-Math
Making Math prettier.

Math seems to be a black and white world, which is not neccessarily true - it can be also very creative and fun.
How to make Math more enjoyable for those who just start learning it or even struggle a bit already?

For example, by creating the calculator that can switch different colors and personalize the experience.

My little daughter was my inspiration with color theme selection as she enjoys pink a lot and uses this calculator to play with numbers and thus having a productive screen time instead of just watching cartoons.

How did I approach building this calculator?

1# I started coding this calculator by creating a proper html structure:
  - <input> elements seemed to be the most efficient for creating calculator fields in combination with "display.value" to set up proper content of the fields
  - the calculation itself is provided by "eval" function that is initiated when user clicks on equal operator "="

2# Then I added the color theme via css file:
  
- apart from basic styling, I also used ":root" and "var(--)" to be able to change colors easily later on

3# In the end I added javascript in order to create a basic toggler for color switching - by using "onclick" function in combination with "classlist" 

This is overall just a first prototype, minimum viable product to be used in our household for now :), but I would further work on to provide more color options, themes, responsiveness etc.


