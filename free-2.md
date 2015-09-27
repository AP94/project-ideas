# Free project 2



This project would be something like the functional equivalent of [scratch][scratch.mit.edu], only as a learning tool for textual coding. It would have a split-screen interface with the area for writing code on the left (maybe in a new language, but most likely in a pre-existing one), and on the right would be an image visualiation of the code, with similar color-coded "building blocks" to show exactly what functions are being called where and what's being passed into them. As code is added, there could be a button to "refresh" the visualization area, which would also be updated when the code is executed.



## The user and a language

This section describes who the project would serve and why a language might be a

good way to meet their needs.



This project would be for people who are trying to learn functional programming, either for their first exposure to CS or for someone who's used to imperative programming.



### What's the need?

_What need is met by your idea? Who are you helping? What is that person's

experience like now? What would their experience be like if you could help 

them?_



Imperative programming seems to be more commonly used for entry-level compter programmers, and while it has its benifits this makes people more hesitant or have more difficulty with undertstanding functional programming, which in some cases can be a more effective tool for the problem they're trying to solve. In addition, some people are more visual learners, and having a view of what's happening in a program would make debugging easier. With a learning tool, picking up a more foreign language would be easier and faster, and new programmers might start out with a deeper understanding of computer programming.



### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_



Interacting directly with a programming language is one of the best ways to learn. So long as it's designed in a way that won't require unlearning later on, and allows for deep understanding of how the language operates, a learning language can be a powerful tool.



### Why you?

_What excites you about this idea? How did you come up with it?_



I've always been interested in teaching/tutoring how people learn, and while I'm not the absolute worst at functional programming languages, learning imperative languages was much easier for me.



### Domain

_Describe the project's domain in five words._



Visualizing general purpose functional languages ?



### Interface (syntax)

_How might the user interact with the language? What does programming look 

like? Why is this the right way to interact with the problem domain?_ 



A program would just be lines of code as per usual.



### Operation (semantics)

_What might happen when a program runs? How does a program interact with the

user? What kinds of errors might occur, and how might they be communicated to

the user?_



The program would update the image when a button is clicked or when the code is executed. If there is an error, it would print the appropriate error message (in whatever style the host language uses), and some problems would be visually represented. For instance, if a function takes in two parameters but only one was given, the user would be able to see that a "piece" is missing; if object types are represented with tabs with the name of the type, then type mismatches would be easy to see.



### Expressiveness

_What should be easy to do in this language? What should be possible, but

difficult? What should be impossible or very difficult?_



It should be easy to write and visualize simple programs. 



### Related work

_Are there any other DSLs in this domain? If not, describe how you know there

aren't and conjecture why not. If so, describe them and provide links. How well 

do they address the need? Are there any particularly admirable qualities of the

language? Are there parts of the language you think could be improved?_



There are a few visualization tools for type inference, but nothing with widespread use. Functional languages just aren't as popular as imperative languages.



## The Project

This section examines whether the idea makes for a good CS 111 project.



I'd argue that it does. It wouldn't be possible to cover everything, but a simple DSL that covers the basics should be possible to make, it's definitely a DSL, and it would help solve the problem.



### Suitability

_If someone were to work on this project, what percentage of their time would be

spent directly engaging in the **language** aspects of this project (e.g.,

making language design decisions), as opposed to "systems" aspects of the

project (e.g., implementing a complicated semantics that doesn't require a lot

of language design)?_



Most of this should involve the language aspects. How to parse the code and create the visualization are the meat of what will be happening, and both of these should be language design decisions.



### Scope

_How big an idea is this? How ambitious is this project?_



This is pretty ambitious. Using an existing language rather than creating a new one would take less work overall, but their libraries are pretty large and by necessity many functions would be left out. The goal would be to have enough basic functionality covered to help people gain a novice understanding of functional programming.



### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea 

project?_



I'd actually be able to use this if all went well. 

The main problem is the scope of what can be done. Because this hasn't been planned out yet, there may be problems that come up later on.

