# The Oregon Trail 🐂 🏜

# Summary / MVP

This app is built to feel like the 90's computer game The Oregon Trail. It will have choose your own adventure elements,
authorization (login), & remember user's scores. At MVP will will have a decision tree that will look like:

![tree](/ReadMeImgs/tree.jpg)

We will be using React.js (front end), JavaScript, React Routing, Fetch, RESTful Routes (Full CRUD), Ruby, Rails (back end) API, Heroku, NPM, Node.js, and Postgresql.

# User Story

1. The user sees a login form, on a pack routed "/login". There are 2 choices, sign in
   on presented form, or click "create account" button.

   a. Already have an account? Put in username and password, then "enter" button.

   b. After clicking create new account, a form to do so replaces the form from before.
   Create your new account and press "enter" button.

2. You have entered the home page, route "/home". There is text about the game, a "start" button, a "stats" button, and a "log out" button.

   a. "Start" button reveals the game, which is a series of options chosen by clicking
   buttons. Each new decision routes to new game page "game/options/:id".

   b. "Stats" button brings you to a page, "/stats" that shows top user's scores (top 10),
   and your scores. From here click "log off" or "home".

   c. "Log off" takes you to original log in form page.

3. Game is over:

   a. "You WIN!" modal appears if won, with a timer that routes to stats page.

   b. "You LOOSE!" modal appears when lost game. Timer takes you to stats page.

# Wire Frames

![wire frame one](/ReadMeImgs/wf1.jpg)

![wire frame two](/ReadMeImgs/wf2.jpg)

![wire frame three](/ReadMeImgs/wf3.jpg)

# Schema

![schema](/ReadMeImgs/schema.jpg)

# Stretch Goals
