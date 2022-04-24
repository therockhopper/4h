---
pageTitle: 'Ibm S3 Bucket Cors'
---

how to set up CORS to enable all origins to use GET

```
ibmcloud cos put-bucket-cors --bucket BUCKET_NAME --cors-configuration '{ "CORSRules": [ { "AllowedMethods": ["GET"], "AllowedOrigins": ["*"] } ] }'  --region us-east
```
