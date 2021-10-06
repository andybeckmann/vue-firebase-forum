# vue-firebase-forum

vue-firebase-forum is an example forum built with Vue on the frontend and uses Firebase Authentication and Realtime Database (rtdb) services.

## Assets

- Mobile-first responsive layouit
- No CSS frameworks/libraries
- 2 original SVG icons

## Screenshots

### Sign in or register
![Signin screenshot](/screenshots/signin.png?raw=true)

### Forum
![Forum screenshot](/screenshots/forum.png?raw=true)

### Topic
![Topic screenshot](/screenshots/topic.png?raw=true)

### Post
![Post screenshot](/screenshots/post.png?raw=true)

## Progress

### Features

- [X] Users can register a new account
- [X] Users are prevented from selecting existing usernames during registration
- [X] Users can reset a forgotten password via email
- [X] Users can change their email address on a settings page
- [X] Users can change their password on a settings page
- [X] Users can create a new posts in predetermined topics
- [X] Users can delete their own posts
- [X] Users can add a comment to an existing post
- [X] Users can delete their own comments on existing posts
- [X] Users can view the total numbers of posts and replies for each topic in the forum
- [X] Users can view the total number of replies for each post in a topic
- [ ] Users are prevented from creating new posts more than once every 5 minutes
- [ ] Users are prevented from creating new comments more than once every 5 minutes
- [ ] Users can upload a single image attachment to posts

### Bugs

- [ ] Deleting last comment on post removes the entire comments field in the post object
- [ ] Users can still register with existing usernames, but only immediately after signing out

## Setup

This app requires a Google account with a Firebase project started. The project needs to have Firebase Real Time Database (RTDB) set up and at least one log in method enabled within Firebase Auth. These project variables need to be stored in .env.

#### Install dependencies
```
npm install
```

#### Compiles and hot-reloads for development
```
npm run serve
```

#### Compiles and minifies for production
```
npm run build
```

#### Lints and fixes files
```
npm run lint
```