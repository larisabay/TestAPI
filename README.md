 #TestAPI
Tested utilizing ReadyAPI
This is simple scenario with one test case that submits two requests:
GET https://ghibliapi.herokuapp.com/films - the response contains some number of films with their unique ids. I parse the id from the first node(film) and pass it to a second request:
GET https://ghibliapi.herokuapp.com/films/{id}
I verified that the requests are successful (HTTP status of the responses - 200)
Logged the request and the response information into the text file. I created some simple Groovy scripts to do so.

