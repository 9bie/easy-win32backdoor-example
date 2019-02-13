# easy-win32backdoor-example
easy win32 backdoor example. support windows service start and real time Command echo.
program will detection self path at the startup.if not in %windir%(WINDOWS installation path).it will be copy it and add camouflage a windows service.
and after.it will use tcp to rebound link to hacker host. you can use `nc -l` to listen the data from our backdoor.
