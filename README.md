## Serving a React Site on Netlify from Github

1. Create your app with: 
  > npx create-react-app name
 
 
2. code your site
3. build your site
  > npm run build
  
4. install serve
  > npm i -g serve

5. run the following:
  > serve -s build
  
6. Create a git repo and add the code:
```
git init
git add .
git commit -m "Initial Commit"
git remote add origin "url to repo"
git push -u origin master
```

7. Create a new netlify app on netlify and add a new site with git. 

# Updating 

1. Update your site

2. Build it again
> npm run build 

3. Serve a folder
> serve -s build 

4. push to github:
```
git add .
git commit -m "Initial Commit"
git push
```

Netlify will update this for you.

