# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
The user does not see the back end but it is what makes the site run (functionality).
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
// your response here
```

Which layer in the MVC pattern communicates with the model?

```bash
The model
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
The views refer to the "view" of the request that the user is doing. However, we
will not use it because all our APIs are servicing routes and we use rails as our API.
```

What does C.R.U.D stand for?

```bash
C - Create
R - Read
U - Update
D - Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
In SQL
```

List at least 5 standard actions that C.R.U.D corresponds to?

```bash
index
create
new
edit
destroy

```

A user action fires a `GET` request for `/persons/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
- A user action fires a `GET` request for `/persons/1`
- Client receives it and communicates it to the controller
- Controller gets it as a string and gives it to the model as an SELECT action
- Model knows what that is and gets an index of the request back to the controller
- The controller returns it to the client, and gives it back to user.
```

What is the command to generate a new rails-api app?

```bash
$ rails new commandsapp
     create
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
rails dbconsole
create
generate migration
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
$ bin/rails generate scaffold Pet name:string age:integer
```
