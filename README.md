# Need to send something quick?

> I will just send an email to myself then go to another device, login and download it! 🥳

### Running live here [https://justa.ml](https://justa.ml)

#### Staging site [justaml.azurewebsites.net](http://justaml.azurewebsites.net)

[![Build status](https://ci.appveyor.com/api/projects/status/3jxpwg2tcwoiaq9b/branch/master?svg=true)](https://ci.appveyor.com/project/mustakimali/justa-ml/branch/master) Production
[![Build status](https://ci.appveyor.com/api/projects/status/notmi7mr5jd27k8d?svg=true)](https://ci.appveyor.com/project/mustakimali/justa-ml-a82xl) Development (Unstable)

[![BuitlWithDot.Net shield](https://builtwithdot.net/project/64/justa.ml/badge)](https://builtwithdot.net/project/64/justa.ml)

## Run from docker hub

```
docker pull mustakimali/justaml
docker run -p 61452:80 justaml
```
Should be running in http://localhost:61452

## Building the code
* Make sure you have [.NET Core 2.1 SDK](https://www.microsoft.com/net/download/core) (Version >= `2.1.401`) installed
* Clone
* `dotnet run` or `dotnet watch run`
* Should be running in http://localhost:61452

## A huge thanks to the following projects

* [Stanford Javascript Crypto Library ](https://github.com/bitwiseshiftleft/sjcl)
* [bignumber.js](https://github.com/MikeMcl/bignumber.js)

... and all other third party libraries used in this project.
