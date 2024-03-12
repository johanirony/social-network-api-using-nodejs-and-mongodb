
# Social Media API

Social network api using node.js express and mongodb. You can post , update, delete ,like ,unlike posts. You have to register and login and also can follow unfollow people.

## API Reference

#### Get your post  

```http
  GET /api/posts/:id
```


#### Post 
You can post using this

```http
  POST /api/post/${id}
```

#### Put 
You can update your post using this
```http
  PUT /api/post/${id}
```

#### Delete 
You can Delete your post using this
```http
  DELETE /api/post/${id}
```

#### Put 
You can like your/others post using this
```http
  PUT /api/post/${id}/like
```




