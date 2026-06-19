# Dynamic-typing Vs Static-typing

The **dynamic-typing** nature of Python makes coding really fast and more flexible, but it can lead to unexpected bugs because type errors are detected only when a program **runs**, not when the program **compiles**.

Since Python determines data types while your program is **running**, type-related mistakes are only discovered at that moment. When a program runs, Python executes your code line by line. If it reaches a line where a certain object is expected to behave in a way it's not able to, Python will **stop** and show an **error**.

In contrast, some languages (C#, C, C++, etc.) **compile** your program before it runs. Compiling means the computer checks your code in advance and prepares it to run. During this step, those languages can catch type errors before the program even starts.
