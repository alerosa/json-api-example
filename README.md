# json-api-example
An example API created with my JSON-API library (http://github.com/ethanresnick/json-api)

# Try it out

1. Clone the repo
2. Ensure Docker is running then run `docker-compose up`
3. Try out the following (for example):
  - `GET http://localhost:5000/` to view the auto-generated documentation
  - `GET http://localhost:5000/people` to view the people collection
  - `POST http://localhost:5000/schools` to add a school
  - `GET http://localhost:5000/organizations` to view the organizations collection, which includes all schools too
  - `GET http://localhost:5000/people/{id}` to view a person, after it's been created
  - `GET`, `POST`, or `PATCH` `http://localhost:5000/organizations/{id}/relationships/liaisons` to view or modify an organization's `liaisons` relationship
