# Objective 
- Create a note taking app where you type in a note
- The note entered should dynamically come under a green Add Note button.
- The note added should have a button so that I can see the whole note in a popup overlay and I can x out of it.

## Challenges
- It was a challenge for me to find a way to find a way to have my input value display on the console.  I need to remember to assign the variable.value to a new variable within my function.
- I just found out that I can create a className in JavaScript.  I needed to do that when I created a new button dynamically inside of JS
- When I have multiple notes. I needed to have each button preform the same thing, but with different text.  The detailsButtonPopUP function uses document.querySelectorAll(".details") to select all the "View Details" buttons on the page and converts the resulting NodeList to an array using Array.from(). Then, it retrieves the index of the clicked button within the array by using indexOf(event.target).
- Tomorrow I will see if detailsButtonPopUp is working correctly
## Steps
- first created my index.html and linked my js and css file to it.
- simple html and css.  CSS in Flex box for phone usage. Not going into details about css and html because this is a JavaScript functionality project.
- Pulled all of my necessary elements into Javascript file.
- Added event listener to see when the Add Note button is clicked.
- created a function for click handling and tested inside the clickHandler function to make sure the event listener is working correctly
- Within my ClickHandler function I create a new variable noteContent to store the value of note.
- Created new div to display strings,<p>tag,and button
- Added another event listener to listen for the clicks of the dynamically created buttons in JavaScript
