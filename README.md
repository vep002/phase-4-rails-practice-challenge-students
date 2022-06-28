# Rails Practice Challenge - Students

## Setup

To download the dependencies for backend, run:

```console
$ bundle install
```

There is some starter code in the `db/seeds.rb` file so that once you've
generated the models, you'll be able to create data to test your application.

You can run your Rails API on [`localhost:3000`](http://localhost:3000) by running:

```console
$ rails s
```

There are no tests for this application, so you'll need to check your progress
by running the server and using Postman make requests.

## Introduction

We're going to build an API for an instructor to manage their students. Create
the following database structure. You will have two models (and their
corresponding tables), `Student` and `Instructor`, with the following
relationships:

✔️ An instructor has many students
✔️ A student belongs to an instructor

The models should have the following attributes (along with any attributes
needed to create the relationships defined above):

✔️ Instructor
  ✔️ name (must be present)
✔️ Student
  ✔️ name (must be present)
  ✔️ major
  ✔️ age (must be >= 18)


## Deliverables

As a user, I can:

- **Instructors**
  ✔️ Create, 
  ✔️ read, 
  ✔️ update 
  ✔️ delete 
- **Students**
  ✔️ Create, 
  ✔️ read, 
  ✔️ update 
  ✔️ delete 
  ✔️ When creating or updating a student, they must be associated with an
    instructor

Follow good API design practices and use RESTful routing conventions. Make sure
to handle errors and invalid data by returning the appropriate status code along
with a message.

## Instructions

- Time yourself while working on the deliverables
- Commit when you hit 75 minutes
- When you have finished all deliverables, commit again.
