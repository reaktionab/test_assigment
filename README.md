# Test assignment

### First of all - import CSV file to database. 

Data must be imported into 3 tables (`emails`, `domains` and `postcodes`). Tables `domains` and `postcodes` must be related with table `emails`. When import is ready, push email to user (you can use https://mailtrap.io/, don't format email, plain text is fine)

In front-end just create form to upload file. Nothing more. It is not task to check front-end skills ;)

### Nice to have
Endpoint to get emails by domain, for example:
```
curl -d '{"domain": "andreasson.net"}' -H "Content-Type: application/json" -X POST http://localhost:5000/api/domain
```

### Tips'n'tricks
Use Laravel. I attach docker configuration, it gives you some tips about possible workflow.

### And last but not least. 
Documenation, please. My 10-years-old daughter should able to understand it, run the stack (in local env) and test if it works. ;)



