# ccgAuth

<!-- Start SDK Installation -->
## SDK Installation

### NPM

```bash
npm add https://github.com/speakeasy-sdks/ccg-v1-ts
```

### Yarn

```bash
yarn add https://github.com/speakeasy-sdks/ccg-v1-ts
```
<!-- End SDK Installation -->

## SDK Example Usage
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

<!-- Start SDK Available Operations -->
## Available Resources and Operations


### [Service](docs/sdks/service/README.md)

* [getstatus](docs/sdks/service/README.md#getstatus) - get status

### [User](docs/sdks/user/README.md)

* [getuser](docs/sdks/user/README.md#getuser) - get user
<!-- End SDK Available Operations -->

### Maturity

This SDK is in beta, and there may be breaking changes between versions without a major version update. Therefore, we recommend pinning usage
to a specific package version. This way, you can install the same version each time without breaking changes unless you are intentionally
looking for the latest version.

### Contributions

While we value open-source contributions to this SDK, this library is generated programmatically.
Feel free to open a PR or a Github issue as a proof of concept and we'll do our best to include it in a future release!

### SDK Created by [Speakeasy](https://docs.speakeasyapi.dev/docs/using-speakeasy/client-sdks)
