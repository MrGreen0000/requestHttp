# requestHttp
### GET herokuapp.com (filter)
GET https://http-practice.herokuapp.com/wilders?language=Java&page=2

### GET herokuapp.com (no filter)
GET https://http-practice.herokuapp.com/wilders?


### Post methode URL-encoded
POST https://http-practice.herokuapp.com/wilders
Content-Type: application/x-www-form-urlencoded

name=Naji%20Mouflih&language=PHP

### Post methode format json
POST https://http-practice.herokuapp.com/wilders
Content-Type: application/json

{
  "name": "Naji Mouflih",
  "language": "PHP"
}

### GET  the wilder afficher le wilder créer à partir de son "id"
GET https://http-practice.herokuapp.com/wilders/1646063

### PUT the wilder methode  json
PUT https://http-practice.herokuapp.com/wilders/1646063
Content-Type: application/json

{
  "name": "Naji Mouflih",
  "language": "Java"
}

### DELETE the wilder
DELETE https://http-practice.herokuapp.com/wilders/1646063
