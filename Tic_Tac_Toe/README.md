React Tic-Tac-Toe Project Reflection

Undertaking the Tic-Tac-Toe tutorial offered by the React website has proven both rewarding and challenging. In this document, I'll provide an overview of my experiences from programming my first project in React and the lessons I learned.

While developing this game, I initially struggled with understanding the "useState" function. "useState" is a "hook" that accepts an initial state as an input and returns a pair consisting of the current state and a function that updates it. More detailes are available in this React document: https://legacy.reactjs.org/docs/hooks-state.html. Upon grasping the concept of "useState", I began to comprehend many parts of the program that relied on the "set" function, returned by "useState". For instance, the "handleClick" function became much clearer.

From this, it is evident that state is a critical concept in React. Before we commence coding, it is necessary to reflect on how many states we require, what they are, and where they should be placed.

Specifically, regarding where we declare states, the tutorial illustrates why we should avoid declaring them at the Square level or even the Board level, and instead do so at the Game level. This approach simplifies the code, making it more comprehensible, less prone to bugs, and easier to refactor. In the context of this particular program, state lifting helps to synchronize data among child components.

I also found the concept of passing functions multiple times to be somewhat confusing. When I attempted to track the sequence of events following a button press, I got lost among the multiple functions. This made the latter part of the program  challenging for me. To surmount this challenge, I intend to revisit this program once I've bolstered my understanding of React through practice on Free Code Camp.