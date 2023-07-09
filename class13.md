# Readings: Message Queues

Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading Socket.io Chat Example

Explain to a non-technical recruiter what the Chat Example (above) does.

- a chat application using Socket.IO, which allows real-time communication between clients and the server.

What proof of life are we getting on the backend from the above app?

- The backend receives proof of life from the app through events and messages exchanged using Socket.IO.

Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

- To send a message to everyone except for a certain emitting socket, you would use the broadcast flag.

## Rooms

What is a room and how might a room be useful?

- A room is a feature provided by Socket.IO that allows you to group sockets together. It can be useful for organizing users or channels.

How do you join a room? - you use the join method provided by Socket.IO.

how do you leave a room? - you use the leave method provided by Socket.IO.

## Namespaces

What is a Namespace and what does it allow you to do?

- mechanism that allows you to separate the communication channels. It allows you to have multiple instances of Socket.IO.

Each namespace potentially has its own what? (hint: 3 things)

- event listeners, emitters, and rooms.

Discuss a possible use case for separate namespaces

- Multi application, where each tenant has its own isolated communication channel for real-time updates or messaging.

| Home Page               | [Home Page](./README.md)                                |
