# Postman + newman + github actions

###  Report 
- To view the report follow the <a href="https://github.com/uxelisol/postman"> link </a>

###  Steps to use
-  Download this repo.
-  Run `npm i` (install node.js dependencies)
-  Run  `npm run test:allure`
-  Run  `allure serve`
- Or import jsonplaceholder.postman_collection.json file to postman 

### Overview of server testing
Route `/posts`. Below is a table of supported operations with `posts` as example resource. 

| VERB     |Route          | Input      | Output             |
|----------|---------------|------------|--------------------|
| GET      | /posts/       | *None*     | **Array**          |
| POST     | /posts        | **object** | **Created object** |
| PUT      | /posts        | **object** | **Updated object** |
| DELETE   | /posts/:id    | **e.g 3**  | **Deleted object** |

### Tests

- Get all posts and verify the status code;
- Create a new post and verify the response;
- Update an existing post and verify the update;
- Delete an existing post and verify the deletion;

### Screenshots
![allure result](https://github.com/uxelisol/postman/blob/main/allureScreenshot1.png)

![allure tests](https://github.com/uxelisol/postman/blob/main/allureScreenshot2.png)

