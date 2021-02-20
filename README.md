# Petful

### Live App: https://petful-client-puce.vercel.app/

### Client Repo: https://github.com/lirondco/petful-client/

### API Repo: https://github.com/lirondco/Petful-Server

### Summary

We are a pet shelter that operates on a FIFO model. We only have cats and dogs in our shelter, and only the one from each animal who has been in our shelter the longest can be adopted. Moreover, you can only adopt when it's your turn in the queue. You can start the process by clicking on the link below and adding your name to the end of the queue. You'll know when it's your turn. Happy adopting!

### Technology Used

* ReactJS
* NodeJS
* JavaScript
* CSS
* HTML
* JSX

### API Documentation

Base URL: https://evening-spire-23721.herokuapp.com/

#### GET - /people

Returns all the people currently in the queue.

#### GET - /pets

Returns all animals that are ready for adoption.

#### POST - /people

Adds a person to the end of the queue


#### DELETE - /pets

Removes the most recently adopted pet/s from the list.
