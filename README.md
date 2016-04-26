#Do

1. go to git hub and create new repository.
2. follow the instruction there and create project folder.
3. install git in the project folder
4. install bower from command line ``npm install -g bower`` && `bower init`
5. hit the enter few times and finish installing bower

Install Polymer
1. `bower install --save Polymer/polymer`
then bower adds bower_componentsfolder in the project file and they put
```
"dependencies": {
  "polymer": "Polymer/polymer#^1.4.0"
}
```
to your bower.json file.
when someone install this project, they can install all plug-ins by installing bower is all of them are listed in "dependencies".

install npm and browser sync
1. `npm init`
npm create package.json automatically.
2. `npm install browser-sync --save-dev`
node_modules will be downloaded.
*same as bower, adding package under the dependencies will make it easier to download all plug-ins at once. (the listed packages would be downloaded when you install npm init.)
