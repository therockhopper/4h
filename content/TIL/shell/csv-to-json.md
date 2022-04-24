---
pageTitle: "Csv to Json"
---

```
# Install requirements
brew install jq && npm i -g csvtojson

# Convert the csv and save it as json
csvtojson ./myCsv.csv | jq . > myJson.json
```
