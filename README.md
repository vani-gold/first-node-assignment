# 1. Define Monolithic architecture
<!-- Defination -->
Monolithic Architecture is like a big container, wherein all the software components of an app are assembled and tightly coupled, i.e., each component fully depends on each other. 
<!-- The Disadvantage of Monolithic architecture  -->
-it's difficult for maintenance because they are dependent on each other.
-To modify an application we have to redeploy the whole application instead of updating parts.
-We cannot scale each component independently.
-If one service goes down, all the others go down aswell

# 2. Explain microservices in your own understanding
Microservices are an architectural style that develops a single application as a set of small services. Each service runs in its own process. The services communicate with clients, and often each other, using lightweight protocols, often over messaging or HTTP
<!-- Advantages of Microservices -->
-Easier Maintenance and Updating
-Increased Agility and Scalability
-Improved Fault Tolerance
-Deployed Independently
<!-- DisAdvantages of Microservices -->
-Increased Development Time.
-Limited Reuse of Code.
-Difficult in Global Testing and Debugging.

# 3. Which of the backend architecture appeals to you and why?
    I prefer the Monolithic architecture because i consider a micreservice more complex with lots of code. As a beginer, I want to have some programming experience before I start looking at the Monolithic architechture.

# 4. Is Nodejs a multithreaded language?
   Node. js runs JavaScript code in a single thread, which means that your code can only do one task at a time. However, Node. js itself is multithreaded and provides hidden threads through the libuv library, which handles I/O operations like reading files from a disk or network requests.

# 5. What does REPL stand for?
    REPL stand for -------> Read-Eval-Print Loop
    A Read-Eval-Print Loop, or REPL, is a computer environment where user inputs are read and evaluated, and then the results are returned to the user. REPLs provide an interactive environment to explore tools available in specific environments or programming languages.

# 6. Create a javascript file and inside the file add code that will log in to the console, your name, your preferred programming language, and where you see yourself in the next 1 year.
    The javascript file name is my-vision.js