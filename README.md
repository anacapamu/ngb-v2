# ngb-v2

## Useful Commands

- `npx quartz build --serve` to preview site at `http://localhost:8080`

## Troubleshooting 
1. Unsupported engine error:
```
npm error code EBADENGINE
npm error engine Unsupported engine
npm error engine Not compatible with your version of node/npm: @jackyzha0/quartz@4.5.1
npm error notsup Not compatible with your version of node/npm: @jackyzha0/quartz@4.5.1
npm error notsup Required: {"npm":">=10.9.2","node":">=22"}
npm error notsup Actual:   {"npm":"11.6.0","node":"v20.18.2"}
```
Run `nvm use 22`
