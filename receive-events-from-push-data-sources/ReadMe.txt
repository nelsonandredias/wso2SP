send an event via HTTP:

curl -X POST http://localhost:5005/SweetProductionEP -H 'content-type: application/json' -d '{"event": { "name": "Jaffa Cake", "amount": 10 }}'
