- to create a access token
```
cd mongo_async_crud
node
require('crypto').randomBytes(64).toString('hex')
```
- same for refresh token


- to update roles for the  user in mongo compass
```
{
  "$set": {
    "roles.Admin": 1984
  }
}

```