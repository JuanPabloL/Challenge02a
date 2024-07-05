## Desarrollo
  La solucion se basa en uno de los laboratorios de la clase, se crea una solucion desde cero y se van agregando los proyectos y clases necesarias.

## Repositorio
  https://github.com/JuanPabloL/Challenge02a

## App Service EndPoint
  https://aswaltchallenge02ajplg.azurewebsites.net/api
  

## Funcionalidad

## Test Crear Log
  http method: POST
  uri:  https://aswaltchallenge02ajplg.azurewebsites.net/api/Log/Create
  body: {  "log": {    "id": "b6558710-158d-40f3-a955-5617a5549912",    "description": "string",    "date": "2024-07-05T13:56:58.962Z",    "type": 0  }}
    
## Test Consultar todos los Logs
  http method: GET
  uri:  https://aswaltchallenge02ajplg.azurewebsites.net/api/Log/GetAllLogs
  
## Test Consultar un log por su identificador
  http method: GET
  uri:  https://aswaltchallenge02ajplg.azurewebsites.net/api/Log/GetLogById?Filter=b6558710-158d-40f3-a955-5617a5549912
  
## Test Consultar logs por su tipo
  http method: GET
  uri:  https://aswaltchallenge02ajplg.azurewebsites.net/api/Log/GetLogsByType?Filter=1