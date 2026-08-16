<!-- meanings what we get from the API -->

S
HTTP/2 200 : it simply means is succesfully get the data from the server
HTTP/2 404 : it means the user made mistake or data is not exists
HTTP/2 500 : it means teh server make an error
content-type: application/json : in which formate we get data or response form usually in json formate
content-length: 292 : it tells us the how many length we data we get here is 292
{ } : this the main body of data which we requested

<!-- Requests 1 -->

Request 1 : curl -i https://jsonplaceholder.typicode.com/posts/1

Response :

HTTP/2 200
date: Sat, 15 Aug 2026 16:53:15 GMT
content-type: application/json; charset=utf-8
content-length: 292
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"124-yiKdLzqO5gfBrJFrcdJ8Yq0LGnU"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=UyhbZ%2F0MO1mJoZS7M4Hj8SWBXp3NkwnJgHEYoqocyDE%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1785191026"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=UyhbZ%2F0MO1mJoZS7M4Hj8SWBXp3NkwnJgHEYoqocyDE%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1785191026"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1785191063
age: 2846
accept-ranges: bytes
cf-cache-status: HIT
cf-ray: a2b9b6e34c159918-AMS
alt-svc: h3=":443"; ma=86400

{
"userId": 1,
"id": 1,
"title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
"body": "quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto"
}

<!-- Requests 2 -->

Request 2 : curl -i https://jsonplaceholder.typicode.com/users/1

Response :

HTTP/2 200
date: Sat, 15 Aug 2026 17:00:16 GMT
content-type: application/json; charset=utf-8
content-length: 509
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"1fd-+2Y3G3w049iSZtw5t1mzSnunngE"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=m23T6Tj%2BQUZnIwphHAim1ChY9yjwiqMeEy5yHiMrfN0%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1785634999"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=m23T6Tj%2BQUZnIwphHAim1ChY9yjwiqMeEy5yHiMrfN0%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1785634999"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1785635057
age: 18502
accept-ranges: bytes
cf-cache-status: HIT
cf-ray: a2b9c12aeff2bd47-AMS
alt-svc: h3=":443"; ma=86400

{
"id": 1,
"name": "Leanne Graham",
"username": "Bret",
"email": "Sincere@april.biz",
"address": {
"street": "Kulas Light",
"suite": "Apt. 556",
"city": "Gwenborough",
"zipcode": "92998-3874",
"geo": {
"lat": "-37.3159",
"lng": "81.1496"
}
},
"phone": "1-770-736-8031 x56442",
"website": "hildegard.org",
"company": {
"name": "Romaguera-Crona",
"catchPhrase": "Multi-layered client-server neural-net",
"bs": "harness real-time e-markets"
}
}

<!-- Requests 3 -->

Request 3 : curl -i https://jsonplaceholder.typicode.com/users/2

Response :

HTTP/2 200
date: Sat, 15 Aug 2026 17:05:50 GMT
content-type: application/json; charset=utf-8
content-length: 509
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"1fd-XTG63SYhaP/Uo6/vgmARnL3rpBk"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=IVocLzpqMxQwk8JHyrLI4PdZm69m%2FPu5LsbyK806Z%2Bc%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1786788692"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=IVocLzpqMxQwk8JHyrLI4PdZm69m%2FPu5LsbyK806Z%2Bc%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1786788692"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 911
x-ratelimit-reset: 1786788703
age: 24858
accept-ranges: bytes
cf-cache-status: HIT
cf-ray: a2b9c9553eed910e-AMS
alt-svc: h3=":443"; ma=86400

{
"id": 2,
"name": "Ervin Howell",
"username": "Antonette",
"email": "Shanna@melissa.tv",
"address": {
"street": "Victor Plains",
"suite": "Suite 879",
"city": "Wisokyburgh",
"zipcode": "90566-7771",
"geo": {
"lat": "-43.9509",
"lng": "-34.4618"
}
},
"phone": "010-692-6593 x09125",
"website": "anastasia.net",
"company": {
"name": "Deckow-Crist",
"catchPhrase": "Proactive didactic contingency",
"bs": "synergize scalable supply-chains"
}
}

<!-- Requests 4 -->

Request 4 : curl -i https://jsonplaceholder.typicode.com/users/3

Response :
HTTP/2 200
date: Sat, 15 Aug 2026 17:07:08 GMT
content-type: application/json; charset=utf-8
content-length: 520
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"208-uuwhfwQMzFzbJr9Pg6DKXae0SXA"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=%2Bs628KfefKiGRtoqMVir8ATxZ%2F6fPDF4RUBGWCXzmhM%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1783600098"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=%2Bs628KfefKiGRtoqMVir8ATxZ%2F6fPDF4RUBGWCXzmhM%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1783600098"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1783600143
age: 12214
accept-ranges: bytes
cf-cache-status: HIT
cf-ray: a2b9cb39bb84e568-AMS
alt-svc: h3=":443"; ma=86400

{
"id": 3,
"name": "Clementine Bauch",
"username": "Samantha",
"email": "Nathan@yesenia.net",
"address": {
"street": "Douglas Extension",
"suite": "Suite 847",
"city": "McKenziehaven",
"zipcode": "59590-4157",
"geo": {
"lat": "-68.6102",
"lng": "-47.0653"
}
},
"phone": "1-463-123-4447",
"website": "ramiro.info",
"company": {
"name": "Romaguera-Jacobson",
"catchPhrase": "Face to face bifurcated interface",
"bs": "e-enable strategic applications"
}
}

<!-- Requests 5 failed request -->

Request 5 : curl -i https://jsonplaceholder.typicode.com/users/9999

Response :

HTTP/2 404
date: Sat, 15 Aug 2026 17:09:29 GMT
content-type: application/json; charset=utf-8
content-length: 2
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"2-vyGp6PvFo4RvsFtPoIWeCReyIC8"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=M5A2nz%2FLNnP50yac64U7ISzzwKEtXYP9EE3XbrXBCdA%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1786786537"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=M5A2nz%2FLNnP50yac64U7ISzzwKEtXYP9EE3XbrXBCdA%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1786786537"
server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1786786543
age: 27231
cf-cache-status: HIT
cf-ray: a2b9cea798c22ae6-SIN
alt-svc: h3=":443"; ma=86400

{}
