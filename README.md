# cache-yarn-subdir

This is a simple action that will cache .yarn/cache given a folder

Usage:

```yaml
  - name: Cache yarn at a subfolder
    uses: taksan/cache-yarn-folder@v1
    with:
      folder: './some-folder'
```
          
