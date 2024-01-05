# Profile

This static site is built using ```mkdocs```.

## Development IDE

Use vscode to edit the application, this uses material design. Select the ```profile``` folder while opening the project in vscode. Install the ```yaml``` editor plugin

### Local deployment for development
Use the following the start a local server for developing and testing the changes.
```
mkdocs serve
```

### Local Build
Use the following command to perform a local build. It is required when adding new directories or new plugin dependencies.
```
mkdocs build
```

### Useful git commands
To check status
```
git status
```
Fetch changes from github
```
git pull
```
Add/remove files
```
git add/rm <file>
```
Commit changes to local repository
```
git commit -a -m "<Comment>"
```
Push changes to github
```
git push origin
```

### Deploy the site to github
Use the following to deploy the site to github
```
mkdocs gh-deploy
```