ReceiveHTTPEventsApp:

send an event via HTTP:

curl -X POST http://localhost:5005/SweetProductionEP -H 'content-type: application/json' -d '{"event": { "name": "Jaffa Cake", "amount": 10 }}'


-------------------------------------------------------------------------------------------------------------------------------------
ReceiveHTTPCustomEventsApp:

send an event via HTTP:

curl -X POST http://localhost:5005/CustomSweetProductionEP -H 'content-type: application/json' -d '{ "sweet": "Jaffa Cake", "batch": { "batch id": "batch1", "count": 10 }}'
