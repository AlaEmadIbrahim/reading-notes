# API Integration

## Dynamic API Server

An Express/Node.js based server designed to be a “model agnostic” REST API server, which can perform CRUD operations on any data model

## Business Requirements

### The API Server must operate as follows:

1. Support all REST/HTTP methods

    - `GET`: Retrieve record(s) from a data source
        - All
        - One (by id)
        - Some (by filtering)
    - `POST`: Create a new record in a data source
    - `PUT`: Update a single full record in a data source
    - `PATCH`: Update part of a single record in a data source
    - `DELETE`: Delete a record in a data source
2. Obey a standard routing structure

    - `/api/v# `where # is the version number of our API

    - `/model` where ‘model’ is the name of the data model to operate on

    - `/id` where ‘id’ is the id number of a specific entity in the data model

3. Obey a standard output format

- Results will be returned in JSON format
- Results will be served with the correct HTTP header - application/json
- The GET Route, when not retrieving by ID, must return a full header, with count ,pages, and a results array
- All other routes must return a single object, representing the state of the entity following the operation

## Technical Requirements

The application will be created with the following overall architecture and methodologies

1. Node.js
2. ES6 Classes and best practices
3. ExpressJS Web Server, built modularly
4. Persistence using a Mongo Database (NoSQL)
5. Mongoose Schemas (data models) to define and model data
6. Mongoose Model “wrapper” class to serve as the API between the express server and the data models themselves.

| Home Page               | [Home Page](./README.md)                                |
