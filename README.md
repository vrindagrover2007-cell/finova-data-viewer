# Finova Data Viewer

## --> Client-Server Model:

The *client-server model* is a distributed network architecture where clients request services and servers provide them.

*Client*: A client is any device or software that initiates communication by requesting data or services from a server.

*Server*: A server is a powerful system that listens for and responds to client requests by delivering data or performing tasks.

The client and server communicate using HTTP (HyperText Transfer Protocol).

The communication flow is: Client sends an HTTP request to the server and the server processes the request. the server then sends an HTTP response back to the client
This request–response cycle happens over the internet.

This is what would happen internally:

The user enters a stock symbol or cryptocurrency name.

The user clicks the Search button.

The client sends a request to the server with the entered value and the server receives the request.

The server fetches relevant stock or crypto data from an API or database and sends the data back to the client.

The client displays the received data inside the UI containers. 

## --> Full-Stack Application:

A *full-stack application* is made of different layers that work together to deliver a complete product to the user. These layers are the frontend, backend, database, and APIs.

~ **Frontend**: Part of the application that the user sees and interacts with.

It is built using HTML, CSS etc and runs in the user's web browser. It has buttons, input fields, texts and different layouts.
The user can click search and it gets sent to the backend.

In this project, the frontend is the Finova Data Viewer UI.

~ **Backend**: Part of the application that works behind the scene, ie, the user has no control on it.

It runs on a server and handles logic and decision-making when it receives a request from the frontend and thereby processes data and prepares responses and sends it back to the frontend.

~ **Database**: It's a place where the application data is stored permanently. 

It stores information such as user data, stock prices, or crypto details and the backend reads data from the database and can update or delete the stored data.
The frontend never talks directly to the database for security reasons.

~ **API (Application Programming Interface)**: API acts as a bridge between different parts of the application and allows the frontend to communicate with the backend.
Can also connect the backend to external services (like stock or crypto data providers) to get the data.

APIs make sure data is exchanged in a structured and secure way.

***This is how these layers interact with eachother:***

User interacts with the frontend, searches whatever they want to.

Frontend sends a request through an API.

Backend receives the request and fetches the data from the database.

Backend sends the result back through the API.

Frontend displays the result to the user.

## Architecture Diagram:

<img width="1920" height="1080" alt="architecture diagram" src="https://github.com/user-attachments/assets/d66841c5-ca24-417b-8cc0-d0533adc50be" />

## My UI in the browser:

![finnova data viewer ui](https://github.com/user-attachments/assets/806f2c53-88c3-430f-94ca-0ecfc4997ec8)

--> As for the screenshots for the git commands, i used vscode to code the html and css part and saved them to my laptop. I then uploaded them to my git repository directly and didnt use commands, hope this is still fine :)
