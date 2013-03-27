PHPStorm Artisan Command Line Helper
====================================

This xml file will provide you with aliases for artisan (the Laravel command line utility) in PHPStorm's console. Once installed on your machine it will provide autocomplete functionality for artisan commands when executed in the PHPStorm command line tools console.

A few things to note
--------------------

- You must have Laravel 4 installed and properly configured for artisan to work correctly.
- This only works for artisan in Laravel 4.
- Your console must be in the same directory as the artisan file or you must create a global path to your artisan file.
- Optional artisan parameters are marked in square brackets []. Required artisan parameters are not enclosed in brackets.

Installation
------------

- MacOSX: Place this file in ```~/Library/Preferences/WebIde60/commandlinetools``` 
- Linux: Place this file in ?
- Windows: Place this file in ?

Once the file is placed in the proper directory you can then open PHPStorm 6 and go to ```Preferences -> Command Line Tool Support``` there you will see the artisan tool. Make sure that it is enabled.

Testing
-------

Open the command line tools console.
Type: artisan
You should see a large list of options appear as a dropdown.
Select artisan help and hit enter twice. (Don't worry if it complains about needing a parameter
You should see the artisan help options as if you had typed the command in your own terminal.

If you see an error with some HTML you will need to open the Command line tool support window again ```Peferences -> Command Line Tool Support``` and edit the "Tool Path". Set a full path to your php binary instead of just "php". 
