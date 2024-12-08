## finn-extractor-api
https://www.finn.no/mobility/item/382633172
Use this link to prepare your pipeline.

you have to extract:
{
  Modellår: 2022
  Kilometer :7 000 km
  Girkasse : Automat
  Drivstoff: Elektrisitet
  finn_code: {code}
}

- Step 1: Your pipeline will receive a POST request from postman with finn code.
- Step 2: It will extract these 4 values from the webpage/html.
- Step 3: After extracting keep the key name as key and value name as value plus add the finn code in the document/dict.

