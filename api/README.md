# Airbnb_clone REST -API

REST API is a software architectural style for Backend.

```
 REST = “REpresentational State Transfer”. API = Application Programming Interface

```

Its purpose is to induce performance, scalability, simplicity, modifiability, visibility, portability, and reliability.

REST API is Resource-based, a resource is an object and can be access by a URI. An object is “displayed”/transferred via a representation (typically JSON). HTTP methods will be actions on a resource.

Example:
```

    Resource: Person (John)
    Service: contact information (GET)
    Representation:
        first_name, last_name, date_of_birth
        JSON format
```

## HTTP Response

In the HTTP Response, the client should verify the information of two things:

    status code: result of the action
    body: JSON or XML representation of resources

### Some important status code:
```
    200: OK
    201: created => after a POST request
    204: no content => can be return after a DELETE request
    400: bad request => the server doesn’t understand the request
    401: unauthorized => client user can’t be identified
    403: forbidden => client user is identified but not allowed to access a resource
    404: not found => resource doesn’t exist
    500: internal server error
```

## Resources

 [restful api design --miguelgrinberg](https://blog.miguelgrinberg.com/post/designing-a-restful-api-with-python-and-flask)

 [Blueprints](https://flask.palletsprojects.com/en/2.1.x/blueprints/)

 [Testing flask apps](https://flask.palletsprojects.com/en/1.1.x/testing/)

 [Flask CORS](https://flask-cors.readthedocs.io/en/latest/)

 []()
