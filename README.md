# Striveblog-CRUD

Backend should now have the possibility to add a comment to an article. 

Mongo's preferred data design should be to embed comments into blog posts if possible, therefore you should implement the following endpoints

    GET /blogPosts/:id/comments => returns all the comments for the specified blog post
    GET /blogPosts/:id/comments/:commentId=> returns a single comment for the specified blog post
    POST /blogPosts/:id => adds a new comment for the specified blog post
    PUT /blogPosts/:id/comment/:commentId => edit the comment belonging to the specified blog post
    DELETE /blogPosts/:id/comment/:commentId=> delete the comment belonging to the specified blog post

Implement pagination in GET /blogPosts route
 

## EXTRA

Play with queries 