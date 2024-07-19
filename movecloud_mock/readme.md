## Database File: db.json

The `db.json` file is a JSON (JavaScript Object Notation) file used as a database in this project. It stores data in a structured format, making it easy to read and write data.

### File Structure

The `db.json` file follows a specific structure to organize the data. It typically consists of one or more JSON objects, where each object represents a record or an entity in the database. Each object contains key-value pairs, where the keys represent the attributes or fields of the entity, and the values represent the corresponding data.

Here's an example of the structure of the `db.json` file:

# JSON Server

JSON Server is a simple and lightweight tool that allows you to quickly create a RESTful API with a full CRUD interface based on a JSON file. It is commonly used for prototyping, mocking APIs, and front-end development.

## Getting Started

To get started with JSON Server, you need to have Node.js installed on your machine. Once you have Node.js installed, you can install JSON Server globally using npm:


npm install -g json-server

## Endpoints

The JSON Server provides several endpoints to interact with the `db.json` file. These endpoints allow you to perform CRUD (Create, Read, Update, Delete) operations on the data.

### GET /{resource}

This endpoint retrieves all the records of a specific resource from the `db.json` file. The `{resource}` parameter represents the name of the resource.

Example: `GET /anomalyDetection` retrieves all the records from the `anomalyDetection` resource.

