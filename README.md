
## Description
Mock server for technical examination.

---

## Instructions:

#### Install dependencies
``` npm install ```

#### Run Server
``` npm run start ```

---

## API Documentation
| Method | Endpoint | Payload | Misc. |
| --- | --- | ---- | ---- |
| POST | /login | ```{ email, password }``` 
| POST | /register | ```{ email, password }```
| GET | /todos | | |
| POST | /todos | ```{ tile, description, createdAt, updatedAt, status }``` | status: (true, false) |
| PUT | /todos/:id | ```{ tile, description, updatedAt, status }``` | status: (true, false) |
| PATCH | /todos/:id | ```{ updatedAt, status }``` | status: (true, false) |
| DELETE | /todos/:id | | |
| GET | /todos/:todoId/comments | | |
| POST | /todos/:todoId/comments | ```{ comment, createdAt, updatedAt }``` |  |
| PUT | /todos/:todoId/comments/:id | ```{ comment, updatedAt }``` | | 
| DELETE | /todos/:todoId/comments/:id  | | |

