# 100 Days Of Code - Log

Day 15: 10 May 2021

Today's progress: Worked on changing prize pot to use linked list instead of vector but now have a bug in the prize collection area. Only works if you collect prizes in the order they appeared!

Thoughts: Using vector initially wasn't the best move. Should have used the linked list straight away. Better planning would have helped.

-------------------------------------------------------

Day 14: 9 May 2021

Today's progress: Finished changing single linked list to double. Added to main code and tested snae still works. Now changing prize pot to use linked list instead of vector.

Thoughts: Pleased with today's progress.

-------------------------------------------------------

Day 13: 8 May 2021

Today's progress: Still looking at changing single linked list to double. Made some progress on it but issues with prev pointer.

Thoughts: Going back to basics a bit with pointers should help.

-------------------------------------------------------

Day 12: 7 May 2021

Today's progress: Removing some old code from Window class. Looking at changing single linked list to double but struggling to get it to work at all in a separate project. Will try again tomorrow.

Thoughts: Struggling to get my head around working with linked lists.

--------------------------------------------------------

Day 11: 6 May 2021

Today's progress: Managed to sort the Pause logic so it's not being checked as often. Also tidied the event handling so the switch statement only changes direction and all the change logic is now in change_direction().

Thoughts: Going well. Need to revisit use of Gets vs direct access as not consistent. Change all to Gets?

---------------------------------------------------------

Day 10: 5 May 2021

Today's progress: Created score controller object and tested it. Score now shows and updates on banner. Started simplifying myApp but struggling a bit with the pause option.

Thoughts: Good progress today - pleased the RenderableText class is working.

---------------------------------------------------------

Day 9: 4 May 2021

Today's progress: Created method in RenderableText class to draw text. Need to test it using score object.

Thoughts: Next I need to take a step back and look at the logic of the game vs the feedback I have.

---------------------------------------------------------

Day 8: 3 May 2021

Today's progress: Getting there. Snake and prizes are rendering on screen using the new draw_element(). Check collision methods not currently working.

Thoughts: May have been easier to restart from beginning but I think doing it this way is helping me understand it more. Especially inheritance.

--------------------------------------------------------

Day 7: 2 May 2021

Today's progress: Slow progress today, compiler errors after each change slowed my down. On the plus side I'm getting better at understanding/troubleshooting the compiler errors. 

Thoughts: Sometimes it helps to take a break if you can't work something out :-)

Link to work: https://github.com/EmmaW74/Snakes (render_class branch)

-----------------------------------------------------

Day 6: 1 May 2021

Today's progress: Continuing to restructure the snakes game. Now have the linked list as a template so I can reuse it with the prizes list - kept as a vector for now as need to change to a double-lined list to be able to remove prizes as they're collected.

Thoughts: Pleased with the new template :-)

Link to work: https://github.com/EmmaW74/Snakes (render_class branch)

-----------------------------------------------------

Day 5: 30 April 2021

Today's progress: Good progress on restructuring the classes to add text/image/block classes and adding the draw method. Also hopefully solved issue with iterating through the snake to draw each segment. Additional feedback from Jordan has also given me lots to look at to improve the game and some corrections to make. 

Thoughts: A good day and looking forward to having extra time to spend over the bank holiday :-)

Link to work: https://github.com/EmmaW74/Snakes (render_class branch)

-----------------------------------------------------

Day 4: 29 April 2021

Today's progress: After reaching out to a colleague and getting some useful feedback I'm going to change my approach and add render_element() to the object classes instead of the myWindow class.

Thoughts: Hopefully back on track :-) 

Link to work: https://github.com/EmmaW74/Snakes (render_class branch)

-----------------------------------------------------

Day 3: 28 April 2021

Today's progress: Still reading through inheritance/virtual functions and testing in a basic program. Haven't found a suitable solution yet so I might be approaching this the wrong way. 

Thoughts: Not much progress today but will keep at it until things click into place :-)

Link to work: https://github.com/EmmaW74/Snakes (render_class branch)

-----------------------------------------------------

Day 2: 27 April 2021

Today's progress: Snakes game - Working on render method that takes different object types. Derived classes are getting inflated with members they don't need. Re-reading inheritance/virtual functions in https://www.learncpp.com/ to see if there's a better way to do this. 

Thoughts: Hoping taking a step back will help me work it out.

Link to work: https://github.com/EmmaW74/Snakes (render_class branch)

----------------------------------------------------

Day 1: 26 April 2021

Today's Progress: Worked on Snakes game. Fixed issue with circular references between MyLinkedList and MyDot (and learned you can't just use #include if the two classes refer to each other - used forward declaration instead).

Thoughts: Good start today. Hoping this challenge will help me get into the habit of making more time for coding. 

Link to work: https://github.com/EmmaW74/Snakes (render_class branch)

----------------------------------------------------
