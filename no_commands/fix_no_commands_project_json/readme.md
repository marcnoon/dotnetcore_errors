# Fix for no commands project json

## works in visual studio 2015 community update 2

The error is gone when pretty much any command is in the commands json stub.

If you debug the project and put a breakpoint in the first line at the Console.WriteLine it will stop there.

## My limitations:

1. I am not 100% sure if run is a command or just a placeholder.  Documentation is still a little sketchy.
2. A command console or bash console is not automatically opened.  
  - to open up a command window or bash console you have to do that yourself
  - maybe for command do something like:
  - cmd /K fix_no_commands_project_json.exe 
  - **note this really didn't work the way I thought a typical console app should work.  Output goes to whatever opens it.


