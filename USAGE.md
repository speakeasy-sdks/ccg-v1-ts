<!-- Start SDK Example Usage -->


```typescript
import { CcgAuth } from "ccgAuth";

(async() => {
  const sdk = new CcgAuth({
    security: {
      httpCCG: "",
    },
  });

  const res = await sdk.service.getstatus();

  if (res.statusCode == 200) {
    // handle response
  }
})();
```
<!-- End SDK Example Usage -->