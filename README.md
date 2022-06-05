# Fundamentals-of-Java
Place to keep the first few modules for Java.  Probably just text editor file uploads, nothing fancy.


**MODULE 1 DISCUSSION

What other computer languages do you know or have heard of? Compare them to Java.

While I have previously taken courses in R, VBA, SAS, Spark, front-end web dev (Javascript, HTML/CSS), I currently work mostly with SQL and Python, so will focus on those.

1) SQL - difficult to compare
SQL stands apart from most other programming languages because of its very specific use, so the differences between SQL and Java are going to be very similar to the differences between SQL and most other languages.  SQL is (literally) a Structured Query Language, so it does not support Object Oriented Programming.  Despite some inefficiencies, it remains the standard way to retrieve data from a relational (aka structured, or rows & columns) database (as opposed to a NoSQL or unstructured database).  One specific difference that is relevant is that SQL does not require a compiler to run, whereas Java does.  Instead, SQL simply has an interpreter that translates the code.

2) Python - a more relevant comparison
Comparing Python and Java is more relevant due to a greater overlap of their use cases: app development (mobile and web), APIs, and data science/machine learning, to name a few.  Java and Python are both object-oriented programming languages (except for control flow statements in Python).  However, they differ in many ways.  Python is dynamically typed, meaning it checks types at runtime, while Java is statically typed, meaning it checks types at compile time.  Speaking of compiling, this is a step that Java code must go through before it can run.  This also comes with greater restrictions than Python: for example, in Java you must declare methods and classes, and you must declare variable types, whereas Python figures out the data types at runtime.  I believe there are other similar examples that I look forward to leanrning as I advance in this class.

We talked about the strengths of the JVM; what do you think are its weaknesses?
1) Running JVM locally on one's machine requires a great deal of memory.
2) The extra step of translating bytecode to machine code - and doing this every time code is run, with no ability to "cache" - decreases speed of code execution.

Final note: I have heard that it is easier to transition from Java >> Python than from Python >> Java, so I will be interested to test that theory!

References: Schildt, Herbert. “1.” Java: A Beginner's Guide, Seventh Edition, McGraw-Hill Education, 2017.
I also read this article: https://www.whizlabs.com/blog/how-does-a-java-virtual-machine-works/#:~:text=Speed%20and%20its%20platform%20specific,to%20other%20high%20level%20languages.

*Reminders: Be sure to include all references and to always use your own words (no copying/pasting from other sources). See the syllabus for information about how your discussion posts will be graded.
