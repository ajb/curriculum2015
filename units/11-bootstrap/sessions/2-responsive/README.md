#Lesson 2 - Responsive Webpages

![Imgur](http://i.imgur.com/hwLWyaBm.png)

## Before class

### Objective

Students will be able to design a website that is responsive to the device it is being viewed on.

### Key points

* Bootstrap makes it easier to create a simple and clean looking page across multiple devices.
* Websites today must be able to reach a large audience regardless of the device they use to access it.

### Assessment

1. Write exit-ticket based off [assessments from current lesson](assessments/exit_ticket.md).

Students will show progress toward reaching the objective based on their performance on the exit-ticket.

### Vocabulary

* Responsive
* Grid System


### References

* http://getbootstrap.com/css/
* https://en.wikipedia.org/wiki/Responsive_web_design

## During class

### Do-now

1. Attendance
2. Return graded exit ticket from previous class
3. [Do-now](assessments/do_now.md)

### Opening

Today we are going to learn how to make a responsive webpage using bootstrap. Can someone please tell me what a responsive webpage is and why it is important?


### Introduction of new material ("I do")

####Grid system

Did you know that webpages you make in Bootstrap have an invisible grid on them? This invisible grid is 12 cells wide regardless of the size of the screen. So if your screen is 12 inches wide each cell will be 1 inch. If your screen is 6 inches wide each cell with be .5 inches wide.

We can utilize this grid system to make your webpage viewable in different sizes such as on a smartphone.

Consider the following code:  


````
<div class="row">  
        <div class="col-xs-12 col-md-6">Hello</div>
        <div class="col-xs-12 col-md-6">World</div>
</div> 
````

In this example, a medium screen would show the words `Hello` and `World` next to each other. However, an extra-small screen would show the two words ontop of eachother.
   
### Guided practice ("We do")
We are going to make a simple yet responsive webpage that consists of three pictures.

1. Open your "first-bootstrap-site" project from last session.
2. Add a page called `3shirts.html` 
3. Find three pictures online of shirts.
4. Place these images on your page using img tags
5. Use the Bootstrap grid system to have these images stack ontop of each other if someone viewed this page on their smartphone.   

### Independent practice ("You do")

Make a webpage called `meme.html` linked in the same first-bootstrap-site workspace.

Your page must include the following:

1. 8-9 of your favorite memes in a Bootstrap grid.
2. When this page is brought up on a computer the grid will be 3x3.
3. When this page is brought up on a phone the grid will be 1x9.
4. One of the images will be emphasized on a desktop computer screen by being inside of a larger cell than the other images.

The image below is an example of a finished webpage:

![Imgur](http://i.imgur.com/tRZdo1pm.png)

#### Exit ticket

Give [exit ticket](assessments/exit_ticket.md).

### Closing

Today you learned how to make pages responsive. This is an increasingly important feature for websites as more and more people access the web via smartphones and tablets.

#### Homework

There is no homework for this lesson.

## After class

* Grade exit-ticket.
* Prepare for next lesson / hand off to next volunteer in rotation.

