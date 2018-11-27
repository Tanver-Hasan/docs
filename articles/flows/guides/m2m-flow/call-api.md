## Call your API

To call your API from the M2M application, the application must pass the retrieved Access Token as a Bearer token in the Authorization header of your HTTP request.

```text
curl --request GET \
  --url YOUR_API_URL \
  --header 'Authorization: Bearer YOUR_ACCESS_TOKEN'
```