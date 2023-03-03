# Json Server Bug ?

```
git clone https://github.com/danielschmitz/json-server-test.git
cd json-server-test
npm install
npm run server

\{^_^}/ hi!

  Loading db.json
  Done

  Resources
  http://localhost:3000/categories
  http://localhost:3000/friends
  http://localhost:3000/books

  Home
  http://localhost:3000
```

Here, db.json has 14 books. Last has id 14. let's delete it

```
curl -X DELETE http://localhost:3000/books/14
```

Now, books has 4 records!!!!!!! Severeval books was deleted... why ?

https://user-images.githubusercontent.com/1509692/222708641-e261794b-ffa8-4bb1-93ec-e4e5132910d1.mp4


