Back End(Node.js)

Now let’s refer the routes.js where we define the REST services. We have three REST services, They are /api/comments/fetchAll, /api/comments/save and /api/comments/delete/:comment_id. So with the name itself, you can understand the purpose of each service.

Before going to this service, We have to create an object model with mongoose which is an object modeling tool designed to work in an asynchronous environment.

Refer the app/models/comment.js. Here I am creating a model object with userName and comment field.