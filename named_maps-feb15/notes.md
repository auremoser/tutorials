3a94862f250b03a5216423d0806a7d7b5ac71d37

curl 'https://auremoser.cartodb.com/api/v1/map/named?api_key=3a94862f250b03a5216423d0806a7d7b5ac71d37' -H 'Content-Type: application/json' -d @config.json

{"template_id":"auremoser@namedmap_tutorial_4"}

curl -X POST 'http://auremoser.cartodb.com/api/v1/map/named/namedmap_tutorial_4' -H 'Content-Type: application/json'

{"layergroupid":"auremoser@6ef71a76@d1d7feb9d04c10d4bc6cfad489ac3472:1421770869329.57","cdn_url":{"http":"ashbu.cartocdn.com","https":"cartocdn-ashbu.global.ssl.fastly.net"},"last_updated":"2015-01-20T16:21:09.329Z"}

http://auremoser.cartodb.com/api/v1/map/auremoser@6ef71a76@d1d7feb9d04c10d4bc6cfad489ac3472:1421770869329.57/{z}/{x}/{y}.png

curl -X GET 'https://auremoser.cartodb.com/api/v1/map/named?api_key=3a94862f250b03a5216423d0806a7d7b5ac71d37'