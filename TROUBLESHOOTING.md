# TROUBLSHOOTING

## Build failure due to correct .net core sdk not available
Install the .net core sdk version as per global.json by running below  
```
.\dotnet-install.ps1 --version 2.2.102 --path "c:\program files\dotnet\sdk"
```
**Note**: *You can find the installed sdk versions by using ```dotnet--list-sdks``` command*.

## Build failures caused by with Python 2.7 dependency not available  
Install npm build tools for windows
```
npm install -g --production windows-build-tools --vs2015
```