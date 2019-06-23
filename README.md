# JPQLCrudRepository

POST
Header
Content-Type	application/json

http://localhost:8081/spring-app/user/article
{
	"articleId":"34",
	"title":"chumma222",
	"category":"java22"
}

GET
http://localhost:8081/spring-app/user/articles
Response
[
    {
        "articleId": 34,
        "title": "chumma222",
        "category": "java22"
    }
]

Note://Here I tested this application with maven build.
Original code https://www.concretepage.com/spring-5/spring-data-crudrepository-example#Run
