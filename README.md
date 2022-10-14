# serverless-test

This site was built from scratch and it shows how to build and deploy an api as a serverless function hosted on Netlify

running site is at 

https://aesthetic-naiad-003226.netlify.app/.netlify/functions/api

and different endpoints can be hit eg

[/ (root)](https://serverless-api-demo.netlify.app/.netlify/functions/api/)
[/test](https://serverless-api-demo.netlify.app/.netlify/functions/api/test)

and even an HTTP POST request can be sent to 

[/testpost](https://serverless-api-demo.netlify.app/.netlify/functions/api/testpost)

if you care to use [`postman`](https://web.postman.co/workspace/My-Workspace~ef76986c-2725-473d-880b-414dc1888e65/request/3042978-b24f225f-e76e-4a49-9f8f-d85c56c3572d) to do this you will get back 

```json
{
    "hello": "hit the POST!"
}
```
