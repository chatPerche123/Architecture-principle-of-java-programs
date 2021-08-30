# Architecture-principle-of-java-programs
Description / some concept of Valéry Guilhem Frémaux book

### First part - Ground concept of a program organization 

I. **Systemic characteristics  of programmating**

Writing a programs requires a global mastery of the software life cycle. It need a variable investment depending of the subject of work (complexity, life span ...).  
A software development is rarely perfect / ideal but it have to be "optimal" according to resources allocated : imposed choice, limited time and resouces ...  
Some choices can be questionable and negativly impact the ongoing project. But it can also be voluntarily limited for different reasons (complexity, allocated time, cost, own knowledge ...).  

1. **Systemic point of view**

A *system*, or *ecosystem*, is complex, more or less autonomous, made of entities intimately linked on different levels, which can interact with each other and with other system.
So a systemic point of view of a system mean an overall view of this specific system :  
it could be an *exploitation system* or *the human body*.

Understanding a system is complex on itself but the informatic tool used include it own too. A system in constitued of different type of data and it can be divised as follow :
data and meta-data.  
The first one live on it own while the other is here to describe and be associated with the first (ie a photo (data) taken at X the Y (meta-data)).  
And it is constitued of *models* which are subset representation of the system. Each one of them is a "core" with it own data (variables), subject to changes and have to put forward a problem that need to be resolve : your data are here to be usefull, resolve a problem.  
A model can be reused to solve different problems as it become more generalist : best use of the time spent (reuse concept).  

*Organization* of the data is important because it grant the possibility to automate tasks . And to do so, times and effort have to be put to the task so it may give more *productivity* in the long run.  
But there is a drawback : the more you organize, the less you produce. It can become very *specialized* too if you have to handle lot's of exceptions and become subject to potential mistakes.

For example: the need to interact with many folders containing files. If you do it by hand, the more file you work on the more time you will spend on it. 
Putting time in organization to automate this task will likely save me time. But, as it get more complex, like handling certain types of file differently, i will have to make exceptions. Paradoxical, the more exception you handle, the more zed become the application.

3. **The big compromises**

"Memory" and "Speed" are two different approaches. The first can save variables that can help you in return to resolve a problem. While the other start from zero and will try to give you the most accurate response in the less time possible. A balance have to be found between the two.

Like we said, organization need time to produce effect and the more you do, the more complex the software become and it may impact the overall coherence of the program.

*Reactivity* is an important concept when you need to operate modification to a software. When a program become very complex, the reactivity drop and tools can be made to ease the process. But these tools can become projects on their own ! (solving problem may lead to more problems).

II. **Basic automate**

Different types of projects need different solutions.  
Scrypting: simple but specialized solutions in a sometime complex environment. Often poorly documented due to the short life or uncertainty (throw-away code) and somewhat very personal and questionable without a peer-review. It can be writed in Bash, Perle or VBScript... 

*Utilitary tool / mono function program* : the start of something as it become more complex than the previous one : few bits of what an autonomous app can be.  

*Integrated / ported application* : add a new "brick" and added value to an already existing product. It can be more or less specialized and may need some work to modify and adapt it for his own environment (software as a service).

*Autonomous application*: work on his own, on an equal footing to the rest, and likely have a low dependency to other applications.

A *software system* is very complex because it is a set of applications sharing common rules and data (elevated imbricated structure) while preserving a coherence.



