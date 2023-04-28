# introductionToNode

1.  Monolithic architechture is an application backend system, where every unit of specialised code that makes up a larger application, is all brought together on one server and it runs its operations from there. Changes made to one aspect of the code could affect the entire code infrastructure.

2. The microservices architecture is the more preffered, albeit more expensive backend system. where each specialised unit of code is seperated into different servers, from where they perform thier operations and send thier outputs to a queue which makes it possible for them to interact with each other.

3. Based on what I've heard, I'm leaning more towards the micro services architecture but I suspect my choice of an achitechture will be determined by the type of application I'm building e.g Is it a blog or a live streaming app?.

4. Node.js is a Javascript framework and although Javascript is a single threaded language. Node.js is made up of other languages like c and c++. This gives node.js access to c++'s libuv library, allowing it to run on up to four threads at a time, therefore node.js is multithreaded.

5. REPL stands for Read, Evaluate, Print, Loop.