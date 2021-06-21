# Social Media API

## Description
An API built for a social media platform using MongoDB, Mongoose, and Express.
This API has support for Users, Friends, Thoughts, and Reactions.

## Usage
1. Make sure you have MongoDB installed on your computer [MongoDB Website](https://docs.mongodb.com/manual/installation/)
2. Install dependencies with `npm -i`
3. Run `npm start` to run the server.
4. Use your browser or an app like [Insomnia](https://insomnia.rest/) to test the API using the routes listed below. You can also import the routes from the included insomnia.json file.

## Routes
**User**
- Get all users:        `GET /api/users`
- Create a user:        `POST /api/users`
- Get user by ID:       `GET /api/users/:id`
- Update a user:        `PUT /api/users/:id`
- Delete a user:        `DELETE /api/users/:id`
- Add a friend:         `PUT /api/users/:userId/friends/:friendId`
- Delete a friend:      `DELETE /api/users/:userId/friends/:friendId`

**Thought**
- Get all thoughts:     `GET /api/thoughts`
- Create a thought:     `POST /api/thoughts`
- Get thought by ID:    `GET /api/thoughts/:id`
- Update a thought:     `PUT /api/thoughts/:id`
- Delete a thought:     `DELETE /api/thoughts/:id`

**Reaction**
- Add a reaction:       `PUT /api/thoughts/:id/reactions`
- Delete a reaction:    `DELETE /api/thoughts/:id/reactions`

## Packages
- express
- moment
- mongoose

## Video Walkthrough
Add the video here!
