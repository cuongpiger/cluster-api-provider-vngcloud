# cluster-api-provider-vngcloud

# Release the manifest

```bash
RELEASE_TAG=v0.0.3

gh release create ${RELEASE_TAG} --title ${RELEASE_TAG} --notes "Release ${RELEASE_TAG}"
gh release upload ${RELEASE_TAG} metadata.yaml
gh release upload ${RELEASE_TAG} infrastructure-components.yaml
```
