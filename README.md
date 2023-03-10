<!-- social media connecting shield -->

[![Facebook][facebook-shield]][facebook-url]
[![Instagram][instagram-shield]][instagram-url]
[![Twitter][twitter-shield]][twitter-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Github][github-shield]][github-url]

![App ScreenShot](https://raw.githubusercontent.com/SamiurRahmanMukul/Complete-MERN-TODO-Application/master/app_screenshot_v1.png)

> **_NOTE:_** The original readme for the project can be found at the bottom of this page.

# Instructions for Local Setup

> **_NOTE:_** All the env configs below, except for the MONGO_URI, can be found in the respective env.example files in this repo

1. In the root of the backend directory, create a .env file with these configs:

```
# APP ENVIRONMENT VARIABLES
APP_NAME = Todo APP
APP_PORT = 5000
APP_BASE_URL = htpp://localhost/
APP_API_PREFIX = /api/v1

# DB ENVIRONMENT VARIABLES
MONGO_URI = [securely provided]**
```

> \*\* MONGO_URI points to a new [mongoDB cluster](https://www.mongodb.com) we've created, which'll host the database that can be used by all COE members. The connection string is all you'll need to connect to the remote DB.

2. In the backend, run `npm install && npm i nodemon` to install [nodemon](https://www.npmjs.com/package/nodemon) along with all other dependencies listed in package.json
3. At the root of the frontend directory, add backend URL to a .env file:

```
REACT_APP_API_BASE_URL = http://localhost:5000
```

4. In the frontend directory, run `npm install` to install all dependencies.
5. Run `npm start` in both frontend, and backend directories.

> **_NOTE_**: A shared DB also means that all TODOs will be shared among all the COE members - in case anyone is surprised to see a todo that they didn’t create.

## Optional Concurrently Setup

If you don’t wanna start both servers separately (as in step 5 above), you can use [concurrently](https://www.npmjs.com/package/concurrently) to simultaneously start both servers in the same terminal window. To achieve this:

1. In the backend directory, run `npm i -D concurrently` to install concurrently.
2. Add the following dev script to backend package.json: `"dev": "concurrently \"npm start\" \"npm start --prefix ../todo-fronted\""`
3. Run `npm run dev` in the backend root directory to start both the front- and the back-end servers.

---

---

# Complete MERN Stack Todo Application

Hello 👋, I'm Samiur Rahman Mukul. At this repository i will be build a `Complete MERN Stack TODO Application ☋`. Using `Node.js, Express.js, MongoDB, React.js, Redux.js & Tailwind CSS`. So are you interested at this project let's connect with me. Thanks

<!-- ahead of main parts -->

### 👨‍💻 Development with MERN Stack Todo Application

- `Backend` - Node.js, Express.js & MongoDB database
- `Frontend` - React.js, Redux.js, & Tailwind CSS

<!-- project directory & live preview link -->

### 🖱️Browse App & API Routes Live URL

|  #  | Projects                                                                                                   | Live Preview                                             |
| :-: | ---------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| 01  | [Todo App](https://github.com/SamiurRahmanMukul/Complete-MERN-TODO-Application/tree/master/todo-fronted)   | [Click Here ↗](https://mukul-todo-app.netlify.app)       |
| 02  | [API Routes](https://github.com/SamiurRahmanMukul/Complete-MERN-TODO-Application/tree/master/todo-backend) | [Click Here ↗](https://mukul-todo-app-new.herokuapp.com) |

<!-- live api documentation -->

### 👉 Live API Routes Documentations

```sh
|--------------------------------------------------------------------------------------------------------|
| METHOD:    URL:                                        // DESCRIPTION                                  |
|--------------------------------------------------------------------------------------------------------|
| GET:      https://mukul-todo-app-new.herokuapp.com/                        // defaults welcome routes  |
| GET:      https://mukul-todo-app-new.herokuapp.com/api/v1/todos-all        // get all todos            |
| GET:      https://mukul-todo-app-new.herokuapp.com/api/v1/todo/:id         // get a single todo        |
| POST:     https://mukul-todo-app-new.herokuapp.com/api/v1/todo/new         // create a new todo        |
| POST:     https://mukul-todo-app-new.herokuapp.com/api/v1/todos-many       // create many todos        |
| PUT:      https://mukul-todo-app-new.herokuapp.com/api/v1/todo/:id         // update a todo            |
| DELETE:   https://mukul-todo-app-new.herokuapp.com/api/v1/todo/:id         // delete a todo            |
|--------------------------------------------------------------------------------------------------------|
```

<!-- my social media links -->

[facebook-url]: https://www.faceook.com/SamiurRahmanMukul
[instagram-url]: https://www.instagram.com/samiur_rahman_mukul
[twitter-url]: https://www.twitter.com/SamiurRahMukul
[linkedin-url]: https://www.linkedin.com/in/SamiurRahmanMukul
[github-url]: https://www.github.com/SamiurRahmanMukul

<!-- shield icon links -->

[facebook-shield]: https://img.shields.io/badge/-Facebook-black.svg?style=flat-square&logo=facebook&color=555&logoColor=white
[instagram-shield]: https://img.shields.io/badge/-Instagram-black.svg?style=flat-square&logo=instagram&color=555&logoColor=white
[twitter-shield]: https://img.shields.io/badge/-Twitter-black.svg?style=flat-square&logo=twitter&color=555&logoColor=white
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[github-shield]: https://img.shields.io/badge/-Github-black.svg?style=flat-square&logo=github&color=555&logoColor=white

<p align="center">
  <strong> HAPPY PROGRAMMING 😀 & I LOVE PROGRAMMING 💖 </strong>
</p>
