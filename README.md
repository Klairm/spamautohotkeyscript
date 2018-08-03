# Spam Script for AutoHotkey 
A script for use with AutoHotkey

# Requeriments:
1. Of course u will need the program AutoHotkey https://autohotkey.com/
2. A notepad for create/edit the script.

# How to use:
As u can see it's really easy code.

1. Download the .ahk 
2. Copy that sentence/word/number or whatever you wan't to spam
2. Then executing the .ahk doing click on the file , will start the script

For stop it just use ESC key

If u wanna edit the speed or the number of message to send just:


``` 
Loop 500 \\ This is the number of messages to send 

{

	Send ^v{Enter}

	Sleep, 1500 \\ This is the speed of the script where 0 is the fastest

	Send ^v{BS}{Enter}

	

        

}


Esc::ExitApp
```
