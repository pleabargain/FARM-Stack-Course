I had to 
* pip install motor

then:
* uvicorn main:app --reload

# file structure of this project
It's strange. It has two readmes.

You have to start FastAPI ```uvicorn main:app --reload``` in one console and ```npm start``` in another. 

# to test
    * works : http://127.0.0.1:8000/docs
    * 

# advice
* watch the video first: https://www.youtube.com/watch?v=OzUzrs8uJl8&t
* understand what is going on with React 
* understand the basics of node



# original readme below with some fixes and a note or two from me

# FARM-Stack-Course

This is the FARM Stack course, where you are going to learn how to build an application from scratch using FASTAPI, React and mongoDB
----------------------------------------------------------
<br/>
FARM stands for FastAPI - React - MongoDB.

WE are going to build our app using FASTAPI for the backend server, React for the frontend client, and MongoDB for the backend database server, so this is for data persistance.

And in my opinion, FARM stack resembles the MEAN stack or the MERN stack, the only difference is the FASAPI because React and MongoDB are the same in the three stacks, 
in MEAN we use Angular and NodeJs, and in MERN we use React and NodeJs.  

FASTAPI is a modern and fast web framework for building APIs, created by Sebastien Ramirez (A nice guy. I met him.) FASTAPI uses ASGI which is the interface between your app and the server and the response time is lightening fast and this is one of the big advantages of having ASGI server implementaion on your side.

Also, one if its big features that it supports coroutines and concurency without the need to import the ASYNCIO module in Python, and in a way it's faster than Express which is NodeJs framework ( and Express is E in the MEAN and MERN stacks ).

FASTAPI also has interactive API documentation, so it helps you testing the different HTTP requests like get post, put and delete visually using Open API which is itself based on JSON schema.

Please follow along in the video to get more details about the course.
https://www.youtube.com/watch?v=OzUzrs8uJl8&t=3483s
Thank you.
BR,
Bek

