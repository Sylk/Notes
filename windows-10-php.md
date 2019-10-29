# Setting up Window 10 to Work with PHP

⚠️Admin rights are required to fulfill the the needs of Chocolatey⚠️

While working on this it's important to remember that you want an easy way to update everything and not get a crazy headache working in a windows environment (which isn't really super easy to do).

So we install a package manager on windows called [Chocolatey](https://chocolatey.org/) because that will allow us to install things quicker. (For understanding what Chocolatey does, (click here)[https://chocolatey.org/docs/getting-started#what-is-chocolatey])

Then follows a long list of installs...

### Packages
```powershell
Cmder
git
GoogleChrome
laragon
phpstorm
```

### Optional Packages that I use for productivity
```powershell
boostnote
caprine
discord
dropbox
f.lux
gitkraken
spotify
vscode
```


There will be trouble with getting NPM to work properly so you'll need to follow the instructions for installing Visual Studio Build Tools.

(The following are threads I encountered that lead me to figuring out the problem, with the last containing the final answer)
[npm install fails on Windows, because of Python · Issue #20024 · nodejs/node · GitHub](https://github.com/nodejs/node/issues/20024)
[javascript - Node npm error on windows looking for tools version - Stack Overflow](https://stackoverflow.com/questions/24182686/node-npm-error-on-windows-looking-for-tools-version)
[Could not install Visual Studio Build Tools · Issue #152 · felixrieseberg/windows-build-tools · GitHub](https://github.com/felixrieseberg/windows-build-tools/issues/152)

```bash
npm install --global --production windows-build-tools@4.0.0
```

To begin actually working on things now, you'll want to launch Laragon, and set up a new project within it.

(You can follow Laragon documentation on how to work on what you're wanting to complete.)[https://laragon.org/]

Cheers!
