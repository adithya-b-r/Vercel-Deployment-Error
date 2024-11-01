##Vercel deployment module not found error

bash ```git rm -r --cached .
git add --all .
git commit -a -m "Versioning untracked files"
git push```

##vercel.json 

bash```{
  "rewrites":  [
      {"source": "/(.*)", "destination": "/"}
   ]
}
```
