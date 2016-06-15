# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash

A backend is used to communicate with the server that is largely responsible for
handling requests from the front end and sending the appropriate resource that is
requested.

```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash

Model

```

Which layer in the MVC pattern communicates with the model?

```bash

Controller

```

Why don't we use views in our interpretation of the MVC pattern?

```bash

Because we will generate the front end as opposed to outputting HTML through the backend.

```

What does C.R.U.D stand for?

```bash
Create
Read
Update
Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash

Controller

```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash

GET
POST
PATCH/PUT
DELETE
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash

The routing determined through 'person/1' chooses the controller that will handle
the request, which then talks to the model that carries out the action, in this case
it retrieves specific data that is requested. The model then returns the resource
to the controller and the controller sends it to the server at which point it can
hand off the resource to the client to display the information.

```

What is the command to generate a new rails-api app?

```bash

rails-api new name_of_app

```

What is the command to start an instance of a rails server?

```bash

rails s

```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash

$ createdb nameofdatabase

$ dropdb nameofdatabase

$ generate migration "CreateXXX"

```

What is the command to scaffold a pet with a name and an age?

```bash

generate migration CreatePet name:sting age:string

```

List two advantages of using serializers? (2 bullet points)

```bash

Serializers replace hash-driven development with object-oriented development

Can very easily convert the important data from an object into a string and write that out to a file

```
