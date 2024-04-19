# [JSL10] Submission: Escaping Vanilla JS: Abstraction Challenge
# Project Objective
The Escapeing Vanilla JS Challenge is an interactive web-based project that focuses on debugging skills, problem-solving and the concept of abstration. We had to navigate through three themed "rooms", each presenting a unique challenge that requires us to dedug and correct the given JavaScript code to proceed. This adventure is themed around escaping the confines of Vanilla JavaScript to advance towards learning React.

![alt text](<[JSL10 Solution].gif>)

# Project Process
* For this project, after accessing the starter code from Github repository, I first read through the steps provided in the instruction.md file and the initial readme.md file.
* I started by first adjusting the id's provided in the first event listner for Room 1 for the two elements fetched from the DOM, I then adjusted the logic for the function called inside the room 1 call back function for accessing the correct book to be passed to the elements content. I adjusted the logic by changing the operator from less than to greater than inside the ternary operators inside the call back function of the reduce method.
* For the second room, I made adjustments to the first set created by adding the 'async' in order to acheive the objectives of the concept being tested which is intersections. I then changed the second argument inside the findIntersection function, since we are testing the two sets created above. I then made changes to the new set created inside the findIntersection function, by adding a filter method which will ensure that the new set will only contain elements which setB has by iterating through setA.
* For the third room, I adjusted the code by adding the async to the call back function for the event listener and then applied the try catch method, inside the try method I added the await operator for the fetch, the conversion of the fetched data to JSON format and the function called which iterates through the data. I then added inside the catch method a string message which is passed to the fetched element from the DOM and also console logged the string message. I then added the await operator to the new Promise.
* I then went an extra mile by creating a div element which I styled to be a loader which is then appended inside the result bar for room three when the room 3 button is pressed, I also before adding the loader I cleared the content of room 3 results element. I then created another element which is a style element which I added to it's content the keyframe's for the animation of the loader and appended inside the head of the document to be accessible throughout the project.
* I then changed my code by assigning the element fetched inside room 3 to a variable which I can use throughout my code.

# Challenges
None, I just had a confusion as to which method to use to test for the intersection of sets. As there were two methods I could use, one being using a for loop with an if statement inside it and the second method being the filter methods which eventually being the one I choose due to the simplicity of it.

# Feedbacks
Overall a good project, which involved different topics we have learned throughout JSL course. Enjoyed working on the additional feature, based on the research I had to do I learned other methods of adding CSS style to JavaScript, it is just unfortunate the other method I wanted to use didn't work.
