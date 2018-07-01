# JSMinfier
A console app that minfies and obfuscates JS, CSS and HTML.
Hello!


This is a quick tool I made for my server and I thought why not share it here. It basically does:

    Obfuscates .js files.
    Obfuscates JS in .html files.
    Minfies .css files.
    Minifies CSS in HTML files.
    Minifies HTML

The program was never intended for releasing so its a bit hard to setup. However, if you follow the steps correctly. You should be good to go!


    Download and install NodeJS (Direct Link)
    Create a new folder somewhere then open a cmd line, then cd to this newly created folder.
    Perform the following the cmd: npm install --save-dev javascript-obfuscator
    You'll see a new folder called node_modules
    Create another folder beside it then download this and put it inside the folder.
    Create a .bat file, name it whatever and put the following contents:

Code

    @echo off
    JsBuilder.exe "C:\Program Files\nodejs\node.exe" "INPUT_PATH" "OUTPUT_PATH"

    You might want to modify the path to node if its installed somewhere else.
    Replace INPUT_PATH with path to the input directory where it will search for the files.
    Replace OUTPUT_PATH with path to the output directory where modified files will be saved.
    Thats it!.. Now just run the .bat file and if everything is correct. You should start seeing it doing the job.


If you have any questions or if you came into any problems. Let me know down below :)


Source Code: https://github.com/Ahmad45123/JSMinfier
