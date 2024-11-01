
## Vercel Deployment Module Not Found Error

To resolve the module not found error on Vercel, use the following commands:

```bash
git rm -r --cached .
git add --all .
git commit -a -m "Versioning untracked files"
git push
```

## vercel.json

Add the following configuration to your `vercel.json` file:

```json
{
  "rewrites": [
    { "source": "/(.*)", "destination": "/" }
  ]
}
```
