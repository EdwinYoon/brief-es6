# brief-es6

### `find` Helper
##### find helper will return the exact the item after the function
``` js 
ex)

const posts = [
    {id: 1, title: "New Post"},
    {id: 2, title: "Old Post"}
]
let comment = { postId: 1, content: "Good Post"}
const postForComment = (posts, comment) => {
    return posts.find((post) => {
        return post.id == comment.postId;  
    })
 }
 postForComment(posts, comment);
//{id: 1, title: "New Post"};

```
========================
### `reduce` Helper
##### reduce helper takes function as an argument. Also it will takes the default vaule of the function's argument 
#####  the data type can be anything ex) 0, [], {}

``` js
let numbers = [10, 20, 30];
let sum = 0;

numbers.reduce((sum, number) => {
    return sum + number;
}, 0);
// 60
```


