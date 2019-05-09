# note

note is a simple bash script that allows you to write "to do" lists and things you want to remember, in your terminal.

!["note"](screenshot.png)

## How to use

Give note execute permission
```
chmod +x note
```

Then just call ./note with the thing you want to note,such as:
```
./note "play football in Wednesday"
```

If you call note without any parameters, it'll display the things you have to note:
```
./note
```

To erase something, pass the ! parameter with the number of the thing you want to forget:
```
./note ! 1
```

Or to erase everything at once, just call remeber nothing:
```
./note nothing
```

## Important

To work as it was intended, you should put it in your scripts folder and add it to the bash config file .bashrc
```
PATH=$PATH:~/scripts
note
```
In this way everytime you open the terminal it will show you the things you have to remeber, and also, you will be able to call it without the ./ 
