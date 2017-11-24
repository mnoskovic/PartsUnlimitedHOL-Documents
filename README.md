# Source

https://github.com/tarunaroraonline/PartsUnlimitedHOL.git

# How to rebuild node-sass (error with python2)

navigate to project root folder and run following commands

```
cd "src\PartsUnlimitedWebSite"
npm install
npm rebuild node-sass
```

# How to solve grunt 9009 error

install grunt globally

```
npm install grunt-cli -g
```

register npm location as environment path

```
take global npm folder where grunt was installed 
- typically c:\users\[username]\appdata\roaming\npm
register url as environment path
- This PC [My Computer] -> properties -> advanced systems settings -> environment variables
- add to user or system "Path", confirm save on all opened windows with "save button" and close all windows

if it still does not work
- refresh variables by opening cmd and running command 'refreshenv'
- close visual studio and open again
```

# How to remove old repo binding

navigate to project root folder and run

```
git remote remove origin
```
