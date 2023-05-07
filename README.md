Download Link: https://assignmentchef.com/product/solved-parallelcomputing-assignment-6-basic-stdthread-usage
<br>
Basic std::thread usage

<strong>1       Minions reporting</strong>

<strong>Question: </strong>Write a program in minions.cpp that takes a number of minion as a command line parameter. Start one thread per minion so that the thread prints “Hello! I am minion <em>x</em>” where <em>x </em>is the number of that particular minion. All these threads should run concurrently. Once all the threads have terminated, create an other thread that says: “hello Minions! I am the Overlord!”.

You can use <em>make run </em>to run your program with 40 minions.

Note that the output may be mangled when all the minion threads are printing; that is fine. Though the message from the overlord should always come last.