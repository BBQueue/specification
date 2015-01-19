Envelopes
=========

Envelopes are small decorators around jobs that contain a return address. This return address is used to communicate a jobs status back to the initiator. Whether that is another job or something else.

Example:

```json
{
  "return_address": "job-123456",
  "job": {
     "task": "echo",
      "payload" : {
          "message": "Hello world!"
      }
  }
}
```
