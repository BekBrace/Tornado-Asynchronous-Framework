Tornado-Asynchronous-Framework
Website : https://www.tornadoweb.org/en/stable/

There is a misconception that all python frameworks do the same thing and are under the same umbrella,
but in fact there are 3 main groups of frameworks in Python: microframeworks for building small application 
but also they're scalable like Flask, Pyramid, Cherrypy and Bottle; others are battery included Full-stack 
web app frameworks like Django, Turbogears and Cubicweb; and the last category is asynchronous frameworks 
for websockets and concurrent connections like Tornado, Sanic , AIOHTTP and Growler.

So, Tornado is an open source framework, but also an asynchronous networking library.
and it was originally developed for a company called FriendFeed, which was acquired by Facebook recently in 2009. 
To understand Tornado we need to know what is it good for.

Tornado is ideal for building apps asking for high performance and several thousand concurrent users;
it can handle 10K connections at once, in addition to that it's non-blocking network IO.
Asynchronous programming was introduced to python since python 3.5 when the asyncio library was introduced
[ I have a video where I am explaining what is ASYNCIO - check it out if you doubt ] !

If all of that does not make sense to you, let me explain everything in under 3 minutes : 

Before anything, you need to know that Asynchronous programming, more specifically async syntax makes you code faster to execute.

Async is a way of Concurrent ProgrammingAsync is one way of doing concurrent programming, 
which means doing many things at once or achieving multiple tasks at once. 


How does Python achieve multiple tasks at once ? 

1 OS makes multi-sharing and multi-tasking happen: One way is to run multiple terminal instances and run your server, 
and all of them will work concurrently in the same time; and your operating system takes care of sharing your CPU resources among those terminal instances.

2 Another way of achieving multiple tasks at once is by using threads.
A thread is a line of execution for several instructions which means that they all share access to common resources, 
and here the operating system intervens to share your CPU with these threads

3 The last way is asynchronous programming which what Tornado does, even though the opperating system will not have any
role here, yet we'll be able to achieve multiple things at once with asynchronous programming

Make sure to check out my last video on tornado Framework
Signin' out, 
Bek 
