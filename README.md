M1 Project Reflections
*Warmup Project:* Flash Cards
*Project Overview:* Create a flash card trivia game
*List out the tools you used:* Classes, Methods, Conditionals, Loops
...

*Write a 1-2 sentence synopsis of what this project does:*
This project runs a text based game that will run through a sequence of trivia questions, asking for an answer each time. 
it runs multiple rounds, with a new question each time, and will track scores and guessing accuracy.

Reflection Questions:
*1. How do you approach solving something when you don’t have all the information?*
    - I start by reading all available information, and write some tests to check my code as I go. I usually try a couple experiments, to see if I can make it work by using tools or methods that I'm already familiar with. If I don't figure out a solution this way, it at least helps point me in the right direction, for what I need to google. I google for things based off of what I've run into with my experimenting; ie. methods I might use, why things are interacting in a specific way, etc. If I'm still having issues, I start reaching out to the rest of the cohort or other support that's available to me.
*2. What was your most effective strategy for getting through blockers during this project? How did this help your process?*
    - When I really start to feel like I'm up against a wall and making no progress, the best thing I've found to do so far is to just walk away for a bit. even if it's just 15-30 minutes of doing something else and I'll start to see issues with my code that I was missing before. 
*3. Tell us about a time that you found yourself in an unproductive struggle, how did you get out of it?*
    - I spent at least 2 hours trying to solve a single problem. I was working with an instance object, I needed to be able to push that object into an array, and still register as an Instance of the Turn class. I wasn't really understanding implicit return so I kept trying to google things, with very little results, and even reached out to the cohort for help. I ended up giving up for the night and just trying to get a good nights sleep, this worked because it helped refresh my brain and also it gave people more time to respond to me and help me learn what I was missing; an understanding of implicit return.
*4. What was the benefit of using TDD while building out this project?*
    - TDD is the only way I was really able to wrap my head around what was expected of me with this project. only having the pry interactions told me what we wanted to be able to do with the files, but not how to do it. TDD helped me plan my approach, organize the components I needed to make, and ensure that each block was working as intended!

*First Solo:* BeatBox
*Project Overview:* Create a program that will make your computer beatbox
*List out the tools you used:* Classes, Methods, while/until/.times loops, Conditional statements
...

*Write a 1-2 sentence synopsis of what this project does:*
    - This project will create an instance object called BeatBox, that will add approved sounds to a linked list. The list can be edited, and can return the data of each node as a string or by playing it in audio form.
*Reflection Questions:*
*1. Pick 1 technical concept you used for this project (look back at our lessons and the learning goals of the project to pick this). Explain what this concept is, how it works, and give an example of where you used this in your code.*
    - Scope: scope is what we have access to, and where we can access it. Scope limits the use of objects to the block of code that they're created in, and the order of operations. Scope was very important in this project. I needed to create variables that would allow me to move through each node in the list, and edit their values. I had to use looping methods to do this, and it was only possible because of the concept of scope, without scope I would have needed to create a new variable for each position in the list, and a way to call it, and I'm not sure if that's even possible. Even if it is, I wouldn't want to figure out how to do it.
*2. What was your process when you got stuck?*
    - my first step was to go into a pry session and try to recreate the scenario that is throwing the error, and see if there's any way I can easily tweek the way I'm using the code to fix it. If I didn't find a solution that way I moved on to using binding.pry inside the method that I was working with. I put a binding at each section of my method block, after the method would finish a portion of it's task, and before it moved on to the next portion. This allowed me to check the return values and data types of each variable I was working with, and better understand why my method was throwing errors. If I still couldn't solve the problem at this point, I would refactor my code and change my approach.
*3. If you had to do this project again, what would you do differently and why?*
    - I want to make sure I'm remembering to make helper methods, I want to learn to use "let" in my RSpec tests. I had to write a lot of repetitive code for my tests, and methods, and I want to do a better job of not repeating myself in my code in general.

*Second Solo:* the_DMV
*Project Overview:* 
List out the tools you used:
...
this project worked mostly with hashes, classses, and iteration. 

Write a 1-2 sentence synopsis of what this project does:
Reflection Questions:
1. Describe the steps you took to dig in to this code base. What was your process? If you don’t feel you had a process, define one that you might like to try next time.
   - my first approach was through nesting .map iteration, by iterating through each element of each hash in the data set, I was able to extract the information that I wanted, but I realized that I was stepping too far into the data set, and I only needed to move down one level to access all the info I needed in a much faster way.
3. What was the benefit of using TDD while building out this project?
   - TDD was important because I really didn't know where to start with writing this code. writing the initial tests helped me outline my approach, and writing the code helped me find more things to write tests for. In the end I wouldn't have been able to find the solution I did without TDD.
5. What was a resource that you used during this project and how did you use this to move your project forward?
   - I always make sure to use the ruby docs as much as I can, I also joined some group study session with my cohortmates that let us solve a few problems together and use that knowledge for the rest of the project.

Paired Paired battleship
Project Overview
List out the tools you used:
...
this project has been the most complex one I've worked on so far. I've used every tool I've used in previous projects, and Michael and I challenged ourselves to research and impliment inheritance, class methods and integers, and Michael even learned how to colorize our rendering in the terminal.

Write a 1-2 sentence synopsis of what this project does:
this project will create and run a game of battleship between the user and a computer. It has 3 points for customization; customizable board sizes, from 4x4(standard) to 9x9; customizeable ships, using custom names and a size between 2 and 1 square less than the max board size; and easy, and normal difficulty settings.
Reflection Questions:
1. What was your pairing style like? How did you manage your Github work flow? What are your thoughts on that workflow?
   - we started with paired programming. At the beginning of the project the tasks didn't seem like they could be easily divided, as many of the pieces were dependent on eachother. Once we got a bit further into the iterations we were able to split up the work and complete it asyncronously. I really enjoyed pairing with Michael, I felt that our development styles meshed well, and we were able to work out a good schedule. He also had some really amazing insights and really helped me deepen my understanding of a few concepts.
3. What skill do you feel you have a better handle on after working on this project? What skill has this project lead you to realize you need more practice on?
   - I think I have a better handle on expressing my thoughts, ideas, and concerns with more technical language. I think I need to work on driver/navigator workflow more, we kind of ended up just watching eachother code and bouncing ideas back and forth a good bit.
5. What strategies help you best work with others? What would you like others to know about how you work best?
   - I think doing a dtr really helped, with the time difference I was stressed about scheduling, but we were able to talk about possible times early on and we didn't end up having any problems. I also realized that I sometimes need to take some asyncronous time to work out all my ideas or else I'll end up derailing us a bit whenever we're making good progress by sugguesting things that might not even work as soon as I think of them.


Group Project
Project Overview
List out the tools you used:
...

Write a 1-2 sentence synopsis of what this project does:
Reflection Questions:
1. Group: What conflicts came up and how did you resolve them? This could look like different opinions on how to code a method, what to name a class, when to do stand ups, or communication breakdowns.
2. Pick 1 technical concept you used for this project (look back at our lessons and the learning goals of the project to pick this). Explain what this concept is, how it works, and give an example of where you used this in your code.
3. Describe your team’s code review process. How did you ensure your end product worked and was of high quality?
