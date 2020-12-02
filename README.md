# Teahouse: An online place to spill the tea

This is the API that enables the Teahouse client.

## Important Links

- [Other Repo](https://github.com/GA-SEI-Team-418/teahouse-client)
- [Deployed API](https://young-headland-96680.herokuapp.com)
- [Deployed Client](https://ga-sei-team-418.github.io/teahouse-client)

## Planning Story

In planning for this project, we came together as a team to discuss how we wanted to handle the requirements we were given. We decided that we'd create an online chat room where everyone can talk to one another in real time. We began by working on the API to ensure that all the routes that we wanted were handled correctly. Then we began to work on the client side to make sure everything looked like we wanted it to.

### Technologies Used

- Node.js
- Express.js
- MongoDB / Mongoose
- Socket.IO

### Unsolved Problems

- Would like to eventually be able to create more chatrooms
- Would like to be able to add emoji picker
- Would like to be able to have users pick a profile picture

### Routes

| Verb   | URI Pattern            | Controller#Action      |
|--------|------------------------|------------------------|
| POST   | `/sign-up`             | `users#signup`         |
| POST   | `/sign-in`             | `users#signin`         |
| PATCH  | `/change-password/`    | `users#changepw`       |
| PATCH  | `/update-username`     | `users#updateusername` |
| DELETE | `/sign-out/`           | `users#signout`        |
| DELETE | `/delete-account`      | `users#deleteaccount`  |

## Images

---

#### ERD:
![ERD](https://i.imgur.com/jlv6mUj.png)
