## PHOTO ROUTES

Base url `/api/photo`

| HTTP Method | URL Path                  | Description         |
| ----------- | ------------------------- | ------------------- |
| GET         | `/getAllPhotos/:group_id` | Get The User Photos |
| POST        | `/savePhoto`              | Shave A Photo       |
| GET         | `/getOnePhot/:photo_id`   | Get A Photo         |
| PUT         | `/editPhoto/:photo_id`    | Edit A Photo        |
| DELETE      | `/deletePhoto/:photo_id`  | Delete the Photo    |

## AUTH ROUTES

Base url `/api/auth`

| HTTP Mehtod | URL Path    | Description            |
| ----------- | ----------- | ---------------------- |
| POST        | `/singup/`  | Sing up like a company |
| POST        | `/login`    | login user/companie    |
| GET         | `/verify`   | Verify auth token      |
| GET         | `/:user_id` | Get the User           |

## PHOTOS ROUTES

Base url `/api/photos`

| HTTP Method | URL Path                   | Description                      |
| ----------- | -------------------------- | -------------------------------- |
| POST        | `/createGroup`             | Create A Group to Share Photos   |
| GET         | `/getYourGroups`           | Get all the groups you belong to |
| GET         | `/getOneGroup/:group_id`   | Get A Group                      |
| PUT         | `/editPhoto/:group_id`     | Edit A Group If You're The Owner |
| DELETE      | `/deletePhoto/:photo_id`   | Delete the photo you uploaded    |
| PUT         | `/joinToGroup/:group_id`   | Join To A Group                  |
| PUT         | `/leaveTheGroup/:group_id` | Leave The Group                  |
