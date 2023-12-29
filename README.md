Buat Basic Jmeter menggunakan rest API endpoint LIST OF ALL OBJECTS, LIST OF OBJECTS BY IDS, ADD OBJECT Pada Link Berikut: https://restful-api.dev/

LIST OF ALL ENDPOINTS:

GET     |         LIST OF ALL OBJECTS      | Request : https://api.restful-api.dev/objects

GET     |         LIST OF OBJECTS BY IDS   | Request: https://api.restful-api.dev/objects?id=3&id=5&id=10

POST    |         ADD OBJECT               | Request: https://api.restful-api.dev/objects
                                             Body Request:
                                              {
                                                 "name": "Apple MacBook Pro 16",
                                                 "data": {
                                                    "year": 2019,
                                                    "price": 1849.99,
                                                    "CPU model": "Intel Core i9",
                                                    "Hard disk size": "1 TB"
                                                 }
                                              }
