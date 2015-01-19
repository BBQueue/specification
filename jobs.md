Jobs
====

Jobs are requests to perform a specific task. They are tiny `Data Transfer Objects` only containing the absolute minimum data to run a task. 

It contains a task identifier and a payload object, for example:

```json
{
   "task": "echo",
    "payload" : {
        "message": "Hello world!"
    }
}
````

The payload object is optional.
