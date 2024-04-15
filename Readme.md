## Steps to Setup

1. Install dependencies

```bash
npm install
```

2. Run Server

```bash
npm start
```

You can browse the apis at <http://localhost:3000>

3. APIs:

POST: localhost:3000/notes 
body: {
    "title": "test title",
    "content": "test content"
}

GET: localhost:3000/notes

GET: localhost:3000/notes/{id}

PUT: localhost:3000/notes/{id}
body: {
    "title": "test title",
    "content": "test content"
}

DELETE: localhost:3000/notes/{id}