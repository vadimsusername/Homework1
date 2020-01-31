# Homework1
For this assignment I refactored the html and css code for a website. One of the major changes I made was to use semantic html elements in place of non-semantic elements. For example I replaced several <div> tags with <section>, <header>, <footer>, <aisde>, <nav>, and <main>. Making these semantic html changes required changes to the css as well. For example in the original code a <div> with a class="footer" is used, where the class .footer is used as the css selector. By changing the <div> to a <footer>, I also had to remove the "footer" class and use the <footer> tag as the css selector, i.e. footer { ...}. Similar changes were made for the other new tags. The other major changes I made was to the use of the id and class attributes. There were two id's which were not being used so I removed them. For the class changes, I noticed that the main content of the webpage was  split into three <div>'s, each with their own unique classes, which all had identical css properties with the same values. Instead I gave the the three <div>'s the same class, which got rid of the use of repeated css code. The side-bar also had the same repetion as the main content, and I made the same type of changes to it. The last changes I made were to add alt attributes to the images and give the website an appropriate title.