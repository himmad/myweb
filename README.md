# myweb
test project
fetch('https://my-json-server.typicode.com/himmad/myweb/db.json')
  .then(response => response.json())
  .then(json => console.log(json))
