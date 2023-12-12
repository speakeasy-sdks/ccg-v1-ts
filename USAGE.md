<!-- Start SDK Example Usage [usage] -->
```typescript
import { CcgAuth } from "ccgAuth";

async function run() {
    const sdk = new CcgAuth({
        security: {
            httpCCG: "Bearer <YOUR_ACCESS_TOKEN_HERE>",
        },
    });

    const res = await sdk.service.getstatus();

    if (res.statusCode == 200) {
        // handle response
    }
}

run();

```
<!-- End SDK Example Usage [usage] -->