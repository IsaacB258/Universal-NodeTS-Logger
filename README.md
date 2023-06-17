# Universal-NodeTS-Logger
This is my first home built logger originally for the purposes of implementing into my twitch bot however i am publishing its source code seperately so anyone who wants to use it can 


Dependencies: 

ANSI-colors
Express



Guide to usage: 

This logger comes with all of its styling already implemented and ready to be dropped directly into any NodeTS project.

all thats needed is for the logger to be imported into the app.ts file already in this repo from this point the logger should be active. 

this logger has 5 total forms of logging these are below:

[INFO]
[DEBUG]
[VERBOSE]
[WARN] 
[ERROR]


to call any of these log types all you need to do in the app.ts file is call it with the log type for example if i was to put an error log to cmd I would just have to write: "this.logger.error(`[MESSAGE]`)" 
this would return something like this in the cmd window when ran. 


![image](https://github.com/IsaacB258/Universal-NodeTS-Logger/assets/106151439/c01322f7-eeb7-462b-944f-ef9ba4ad5e55)

The same commands are used for all 5 log types. 

in the "Logger.TS" there is functionality to adjust what messages you will see in the cmd window as pictured here:

![image](https://github.com/IsaacB258/Universal-NodeTS-Logger/assets/106151439/71c11a34-e3db-4655-9cdd-62a208b61869)

to adjust the verbosity of the logging you can simple change the last part of this command to reflect the lowest level of logging you want for example if you only want info and error messages you would just change this to `LogTypes.Error`

Side note: Info messages are coded to always be displayed regardless of verbosity 



Future updates planned: 

this project is intended to evolve organically as i implement accross multiple projects all evolutions will be commited here. 

1. Implementation of a short and long time/date option 



