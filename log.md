# 100 Days Of Code - Log

Day 35: 30 May 2021

Today's progress: Part 1 (30 mins) Cleared compile errors so now have Game Over text appearing via the new class and using font and colours from Dimensions class.

Part 2: 

Thoughts: Feels like code will be tidier once I've done game over and moved things like fonts and colours into measurements (Dimensions) object. 

---------------------------------------------------------------

Day 34: 29 May 2021

Today's progress: Working on game over - moving method across to new class and fixing compile errors.

Thoughts: Busy day today so pleased I still fitted an hour in :-)

-----------------------------------------------------

Day 33: 28 May 2021

Today's progress: Started a class to control the game over part of the program.

Thoughts: Feels like a class will make it easier to manage the game over.

-----------------------------------------------------

Day 32: 27 May 2021

Today's progress: Continued working on using SDL_TEXTINPUT for user to enter their name if they get a high score. Sorted issue with cstr() - problem due to scope of string.

Thoughts: Initially started this in score controller but think a separate class might be better to co-ordinate the whole game over section.

-----------------------------------------------------

Day 31: 26 May 2021

Today's progress: Not much progress today. Started looking at using SDL_TEXTINPUT for user to enter their name if they get a high score. Issues with making score controller draw function work with more than one text field.

Thoughts: Issue something to do with passing string as a parameter to the function.

-----------------------------------------------------

Day 30: 25 May 2021

Today's progress: Working on game over window - replacing image with SDL text. Managed to get Game Over text to appear on screen gradually using source and destination rectangles.

Thoughts: Pleased with progress. Probably need a game_over class to handle graphics. Also maybe expand score class to retain and update high scores.

----------------------------------------------------

Day 29: 24 May 2021

Today's progress: Good progress today. Finished extra checks to snakes game so prizes don't appear on top of the snake (did a bit of this yesterday after I'd logged my progress) and started on improving the Game Over window.

Thoughts: Starting to think about what to try next when snakes is finished. Bought a reduced course on Udemy that covers some things I haven't really looked at yet.

----------------------------------------------------

Day 28: 23 May 2021

Today's progress: Sorted text on Welcome screen and finished border collision option so you can press B on the welcome screen to choose. Learned you need to check for key down in addition to which key otherwise you get multiple instances of the key press.

Thoughts: Pleased with Welcome screen. Next need to look at check to stop prize appearing on top of snake.

----------------------------------------------------

Day 27: 22 May 2021

Today's progress: Created intro page controller to manage the user options. Got text to show on screen but need to look at better font (bold etc)

Thoughts: Good progress today.

----------------------------------------------------

Day 26: 21 May 2021

Today's progress: Started on adding new option to snakes game to choose if snake crashes on edge of screen or wraps around - updated the functions, next need to add the option to the welcome screen.

Thoughts: Getting there :-)

----------------------------------------------------

Day 25: 20 May 2021

Today's progress: After a few issues the iterator is working in the snakes game :-)

Thoughts: Pleased I worked out why the iterator was stopping (due to removing element then trying to iterate further).

----------------------------------------------------

Day 24: 19 May 2021

Today's progress: Really pleased my iterator now works in my test project. Now just need to get it to work in the snakes game. Feel like I've learned something this week but definitely need to review the pointer/reference part of the C++ course.

Thoughts: Need to improve my knowledge of pointers, references and shared pointers.

----------------------------------------------------

Day 23: 18 May 2021

Today's progress: Admitted defeat and asked for help. Looks like it was the range based for loop was looking to the shared pointer rather than the container. Making progress now - just have an exception error to sort.

Thoughts: Need to improve my knowledge of pointers, references and shared pointers.

----------------------------------------------------

Day 22: 17 May 2021

Today's progress: Still can't see why the iterator isn't working. Think I'm going to have to ask for help tomorrow. 

Thoughts: Feels like I know how it should be working but can't see where it's going wrong.

-----------------------------------------------------

Day 21: 16 May 2021

Today's progress: More reading about custom iterators. Starting to understand it a bit more but still can't get begin and end functions to work. 

Thoughts: Feel like I'm getting there, just need to learn about it a bit more in-depth.

-----------------------------------------------------

Day 20: 15 May 2021

Today's progress: Only 1 hour today. Looking into creating an iterator for the linked list. Struggling with getting the begin function to work.

Thoughts: Not really understanding the custom iterator yet. Need to do more research.

-----------------------------------------------------

Day 19: 14 May 2021

Today's progress: Further work on dimensions class, also added default snake length and speed. Next need to look at how I can get my linked list to work with an iterator.

Thoughts: Getting there, a lot of the feedback is now actioned. Still need to tidy up Game over graphics and add option for border collision.

Link to work: https://github.com/EmmaW74/Snakes/tree/improve_accuracy

------------------------------------------------------

Day 18: 13 May 2021

Today's progress: Not much progress today, created new class to hold dimensions such as screen size, dot size etc and started to replace fixed values with variables from the new class.

Thoughts: Need to spend more time on this over the weekend.

-------------------------------------------------------

Day 17: 12 May 2021

Today's progress: Busy day today so just tidied code a bit, getting rid of old commented out code and checking for memory leaks.

Thoughts: Next steps are to make the collision detection more accurate and review how fixed values are handled (screen width, dot size etc).

-------------------------------------------------------
Day 16: 11 May 2021

Today's progress: After 2 hours of troubleshooting I've fixed the collect prizes bug. Need to tidy up some commented out code but I'll do that tomorrow.

Thoughts: Glad I fixed the bug.

-------------------------------------------------------

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
