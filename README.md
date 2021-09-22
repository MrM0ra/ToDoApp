# FlaskDemo
Flask app demo for the course advanced web programming developed with python and flask as backend API end react as frontend

## Adding tasks
Go to: /task
Method:'POST'
body/JSON:'taskName -> string,completed -> boolean'

Example:
localhost:5000/task
POST
{
  'taskName':'take a shower',
  'completed':false
}

## Deleting tasks
Go to: /task/id
Method:'DELETE'
Where id is the id for the task you want to delete

Example:
localhost:5000/task/1
DELETE
deletes the task with the id 1

## Searching tasks
Go to: /task/id
Method:'GET'
Where id is the id for the task you want to search

Example:
localhost:5000/task/1
GET
returns the information for the task with the id 1

## Get all tasks
Go to: /task
Method:'GET'
