# service

### Available Operations

* [getstatus](#getstatus) - get status

## getstatus

get status

### Example Usage

```typescript
import { CcgAuth } from "ccgAuth";
import { GetstatusResponse } from "ccgAuth/dist/sdk/models/operations";

const sdk = new CcgAuth({
  security: {
    httpCCG: "",
  },
});

sdk.service.getstatus().then((res: GetstatusResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```

### Parameters

| Parameter                                                    | Type                                                         | Required                                                     | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| `config`                                                     | [AxiosRequestConfig](https://axios-http.com/docs/req_config) | :heavy_minus_sign:                                           | Available config options for making requests.                |


### Response

**Promise<[operations.GetstatusResponse](../../models/operations/getstatusresponse.md)>**
