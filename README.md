# SocialNetwork-API

## Description

An backend application used to structure elements of a social media site. Using MongoDB, you can create a user, write out thoughts, and add reactions to other people's thoughts. Additionally, friends can be added and removed from an account.

## Usage

Choose your request method on Insomnia and issue the request to one of the API endpoints.

For dealing with users, the endpoint is

```
http://localhost:3001/api/users
```

For managing thoughts:

```
http://localhost:3001/api/thoughts
```

For adding and deleting friends, the endpoint is

```
http://localhost:3001/api/users/:userId/friends/:friendId
```

For adding and deleting reactions:

```
http://localhost:3001/api/thoughts/:thoughtId/reactions (/:reactionId for deleting)
```

## Demo

![Here](./assets/demo.webm) is the link to the demo video

## License

This application is licensed under the MIT license
