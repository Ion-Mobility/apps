# saleor-app-monitoring

## 0.3.2

### Patch Changes

- dca82bb: Update app-sdk to pre-0.34.0. Update Async Webhooks to use new API

## 0.3.1

### Patch Changes

- 2755ed2: Added extra padding on top of the app so it has some space between content and dashboard header

## 0.3.0

### Minor Changes

- 2d23480: Remove TitleBar component from apps, because it is moved to Dashboard, outside of iframe context

### Patch Changes

- Updated dependencies [2d23480]
  - @saleor/apps-shared@1.3.0

## 0.2.0

### Minor Changes

- 289b42f: Breaking change for app maintainers: VercelAPL can no longer be set for the app since it's deprecated and will be removed in app-sdk 0.30.0. As a replacement, we recommend using Upstash APL or implementing your own.
  Read more about APLs: https://github.com/saleor/saleor-app-sdk/blob/main/docs/apl.md

## 0.1.1

### Patch Changes

- Updated dependencies [5fc88ed]
  - @saleor/apps-shared@1.2.0