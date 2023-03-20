# BackEnd-Notes


Node js commands

npm init           

npm install -g nodemon                           // automatically run program 

npm ./index.js


nodemon ./index.js                              // nodemoon run indx file now i dont have to use  node ./index.js cmd

rs                                              //restart server using nodemon


if i dont want to use require method and i want to use import export
then change type=commonjs to type = module     inside the package.json  now require method will not work



# nodemon not working #
125


Error on terminal: nodemon.ps1 cannot be loaded because running scripts is disabled on this system. For more information, see about_Execution_Policies at https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-7.2

use it in powercell

Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

go throught this link
https://stackoverflow.com/questions/63423584/how-to-fix-error-nodemon-ps1-cannot-be-loaded-because-running-scripts-is-disabl
