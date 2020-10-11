# Keyword_Spotting

Postma Request:

curl -X POST \
  http://localhost:6500/predict \
  -H 'Content-Type: application/json' \
  -H 'Postman-Token: d1288060-2c4b-4293-bd9e-618ba0f4726a' \
  -H 'cache-control: no-cache' \
  -d '{
	"text": "I left school bus yesterday at 5 in evening"
}'


Response:

{
    "Keyword": "[('school', 7, 13), ('bus', 14, 17)]"
}
