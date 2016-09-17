# Online Calculator In-box Test

This project consists of a NetBeans web project that includes a Javacript calculator application.  Currently, this calculator runs entirely in
javascript on the client-side.  Your job, is to modify this application so that the calculation of the equation is performed via AJAX in Java
on the server-side.

Specifically, when the user hits the "=" button, it should send an AJAX request to the server with the equation.  The server should process this equation, and return the result to the client
as JSON.  The client will then place the result in the calculator viewport.  When finished, the calculator should appear to function exactly the same as it does right now.  The only difference is 
that the calculation will be performed on the server-side.

## Rules:

1. You may include any third-party javascript library you like to help with the AJAX request.
2. While you are allowed to include any java library you like on the server-side to help with the calculation of the equation, this is not required.  You should be able to 
calculate the equation without including any 3rd-party libraries.


## Instructions

1. Fork this repository on GitHub
2. Complete the assignment on your local machine.
3. When finished, post your result to GitHub, and create a pull-request to merge the changes to this repository.

## Suggested time to complete

30 minutes.

## Recommended Tools

1. Netbeans 8.1 or higher
2. JDK 8
3. Git
