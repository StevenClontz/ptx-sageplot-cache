Error with sageplot caching for PDF format. To replicate:

- Open codespace
- Let everything install
- `pretext build print` (works)
- delete `generated-assets`
- `pretext build print` (fails)
