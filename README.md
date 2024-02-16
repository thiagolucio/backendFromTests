# backendFromTests

A backend Json Serve from test in my professional local projects



Json Placeholder

https://jsonplaceholder.typicode.com/



Exemplo de como rodar um json com jsonplaceholder

    json-server --watch users.json --port 3001
    
    json-server --watch people.json --port 3001
    

por exemplo vc poderá colocar isso no seu script do package.json do projeto. Como no exemplo abaixo:

`  "scripts": {
    "start": "json-server --watch db.json --port 3001",
    "users": "json-server --watch users.json --port 3001",
    "people": "json-server --watch people.json --port 3001",
    "test": "echo \"Error: no test specified\" && exit 1"
  },`
