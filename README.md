
# Disc Golf Bag Randomizer

### This randomizer was created for YouTuber TQM_gg as they completed a disc golf challenge with Peachy Disc Golf. Check out the finished disc golf episode on YouTube. For every hole, the application can be used to randomize a disc from the preinputed arry of discs in TQM's bag.

**Link to project:** https://tqmdiscgolf.netlify.app/
**See it in action:** :tv: https://www.youtube.com/watch?v=Pv7tYN6EpvA

![randomizer button and name of returned disc](https://github.com/lfrendahl/DiscGolfRandomizer/blob/main/randomizerCover.jpg)

## How It's Made:

**Tech used:** HTML, CSS, JavaScript

The main concept revolves around creating a function that uses the math randomize functionality to select an element from the inputed array. To add flair though, you will notice that when pushed a number of disc choices are flashed on the screen as if the computer is filtering through the list before selecting a final choice. This was achieved by using the setIterval function to run the randomize function with a count feature. 

As the website was going to be accessed on a phone, using media queries was very important to allow it to shine when viewed both vertically and horizontally on a mobile device. 

## Optimizations
*(optional)*

This project was requested with a quick turn around, which is why the disc array was hardcoded in. To optimize this application, I would add a way for players to enter the discs that they would like to be able to randomize through. An alternative that saves time on the part of the user is to allow them to enter the number of discs they have and generate a disc to pull from left to right. 

The other suggestion for project optimization is to allow the user to toggle if they would or would not like discs to be repeated. 

## Lessons Learned:

I initially built from a laptop screen and had to make a number of different CSS decisions to update the finished product for mobile. Planning a mobile first layout for a mobile-centric website is a great plan. 


