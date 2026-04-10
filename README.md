# Ice-Task-2-RubberDuck-AI 
1.	What is a class?
A class is a blueprint for creating objects and provides values for variables and implementing the objects behaviour. 
2.	What is an object?
An object is an instance of a class that represents their state and behaviour
3.	What does your constructor do?
A constructor is the blueprint for an object attribute.
4.	Why is it parameterised?
Parameterised is used to define states of an object when initialised
5.	What is the difference between a parameter and a field?
A parameter is a variable defined in a method whilst a field represents the state of an object.
6.	Why are your fields private? 
The fields are private so that the variables can only use in this field. It restricts the access of a classes’ internal data.


You are my rubber duck. Do NOT teach me. Do NOT give definitions. Do NOT fix or rewrite my code. Only ask short questions if my explanation is unclear or inconsistent. Your job is to detect possible misconceptions.
Got it.
What are you working on right now, and what’s your current understanding of what’s happening?

I made a code that is a prototype example of a program a bookstore might use . This code has a main method and a book class. The main method allows one to create an instance of the book class.
The code in the class allows for the blueprint of the objects whilst the main method allows the object to be created. 

When you say “allows one to create an instance,” who or what is actually doing the creating in your setup?
And what role do you think the main method plays at runtime versus the Book class definition?
The user has to input the information the system asks for, such as the book title and price, via the use of scanners 

Where exactly does the user input go first—into the main method or directly into the Book object?
And once the input is captured, what decides whether it becomes part of the object or just temporary data?

The main method, although the data added is temporary

What makes it temporary in your mind?
At what point do you expect the data to stop being “temporary” and become part of something that persists?
And what is responsible for that transition in your code?

When the code stops running. The user added information is not stored 

When you say “not stored,” where were you expecting it to be stored in the first place?
And in your design, what’s supposed to remember the book’s title and price after the scanner finishes reading them?

You can't store the user input at this stage of the program.

What makes you think storage isn’t possible at this stage?
Are you equating “program ends” with “no memory exists anymore,” or are you thinking there’s no structure in your code that could hold values while it’s running?

I can learn about how to store the input, then make a way to store it in a file or even a table. 

What do you mean by “store it” in your current design—are you thinking of something happening during runtime, or only after the program ends?
And when you mention a file or a table, where do you imagine the book data lives between being typed in and being written there?

When it ends

If everything only “exists when it ends,” how does the program decide what to write into a file in the first place?
And when you think about the moment right before it ends, is there still anything holding the book data?

You can access the file the input is stored in and delete it

What file are you referring to—do you already have one being created during the program run, or are you imagining one appears after the program ends?
And when you say “delete it,” are you thinking the input lives in the file only, or could it also still be in memory before that point?

file only 

So in your model, the input never exists anywhere except the file—how does it get into the file at the moment the user types it?
And what is responsible for writing it there if nothing exists in memory at that stage?

The scanner and the user 

What part of the scanner is doing the “writing,” and where is that action happening?
And when you say “the user and scanner,” are you treating them as separate steps, or as one continuous flow?


The explanation of the code:
I made a code that is a prototype example of a program a bookstore might use . This code has a main method and a book class. The main method allows one to create an instance of the book class. The code in the class allows for the blueprint of the objects whilst the main method allows the object to be created.


My reflection:
When testing the AI to detect any misconceptions, the AI at first asks quite  note worthy questions that can be easily answered or takes a bit of thinking to answer. At first the AI is a bit helpful making you think of certain things that you told it that you haven’t really gotten the attention it  should have gotten. Whilst trying to explain that the user input is temporary and is not saved when the code stops running, the AI starts to get confused, at one point the AI got incredibly philosophical. At one point the AI kept circling back to a part of the explanation of my code that wasn’t even mentioned. The AI kept looping back to wanting to know about how the book objects are stored. by the end of the conversation, I felt bad for the AI I thought it was having a stroke. In the end the AI didn’t clear up anything it just made me confused. 
