#  CRUD

****CRUD stands for Create, Read, Update, and Delete, which are the four basic operations of a database. This repository contains a simple CRUD application written in JavaScript that demonstrates how to perform these operations.****


## Getting Started

To run the application, you will need to run the node and db services with the command `docker-compose up -d`. These service will initialize a container named `store_manager` and another named `store_manager_db`.

Install the dependencies inside the `store_manager` container with `npm install`.

## Running the Application

To start the application, you will need to run the following command: `npm start`

This will start the server and you will be able to access the application at [http://localhost:3000](http://localhost:3000/).

## Reading a Resource

To read a resource, you will need to make a GET request to the endpoint `/resources` or  `/resources/:id` where  `:id`is the id of the resource you want to read.

In case of this application, the resource can only be a *product* or a *sale*.

## Updating a Resource

To update a resource, you will need to make a PUT request to the endpoint `/resources/:id` with the updated data in the request body, where `:id` is the id of the resource you want to update.

## Deleting a Resource

To delete a resource, you will need to make a DELETE request to the endpoint `/resources/:id`, where `:id` is the id of the resource you want to delete.
 

> **This application serves as a simple example of how CRUD operations can be implemented in JavaScript, and can be used as a starting point
> for building more complex applications.**
