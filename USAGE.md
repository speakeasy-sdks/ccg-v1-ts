<!-- Start SDK Example Usage -->


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
<!-- End SDK Example Usage -->