# User
(*.user*)

### Available Operations

* [getuser](#getuser) - get user

## getuser

get user

### Example Usage

```typescript
import { CcgAuth } from "ccgAuth";

(async() => {
  const sdk = new CcgAuth({
    security: {
      httpCCG: "",
    },
  });

  const res = await sdk.user.getuser();


  if (res.statusCode == 200) {
    // handle response
  }
})();
```

### Parameters

| Parameter                                                    | Type                                                         | Required                                                     | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| `config`                                                     | [AxiosRequestConfig](https://axios-http.com/docs/req_config) | :heavy_minus_sign:                                           | Available config options for making requests.                |


### Response

**Promise<[operations.GetuserResponse](../../models/operations/getuserresponse.md)>**

