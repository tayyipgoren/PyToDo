# PyToDo
Python3 To-Do cli app

## Running
```
pip install -r requirements.txt
```

```
python main.py
```

## Usage
### Start Screen
```
██████╗ ██╗   ██╗    ████████╗ ██████╗       ██████╗  ██████╗                                                                                                                                                                       
██╔══██╗╚██╗ ██╔╝    ╚══██╔══╝██╔═══██╗      ██╔══██╗██╔═══██╗                                                                                                                                                                      
██████╔╝ ╚████╔╝        ██║   ██║   ██║█████╗██║  ██║██║   ██║                                                                                                                                                                      
██╔═══╝   ╚██╔╝         ██║   ██║   ██║╚════╝██║  ██║██║   ██║                                                                                                                                                                      
██║        ██║          ██║   ╚██████╔╝      ██████╔╝╚██████╔╝                                                                                                                                                                      
╚═╝        ╚═╝          ╚═╝    ╚═════╝       ╚═════╝  ╚═════╝                                                                                                                                                                       
  ----------------------   ver 0.05  -----------------------                                                                                                                                                                        
      ------------------    By. TG   -------------------                                                                                                                                                                            

[1]  List To-Do                                                                                                                                                                                                                     
[2]  Remove item from To-Do                                                                                                                                                                                                         
[3]  List Done                                                                                                                                                                                                                      
[4]  Recover from Done                                                                                                                                                                                                              
 
[9]  Help                                                                                                                                                                                                                           
[0]  Exit                                                                                                                                                                                                                           
~/$>  [Selection]
```

## Todo
Todo list must be in the folder "todo/", every line in the files will be treated as an indiviual item
Example todo.txt:
```
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
```
Example output:
```
[1]     Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod                                                                                                                                                    
[2]     tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,                                                                                                                                                
[3]     quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo                                                                                                                                                     
[4]     consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse                                                                                                                                                   
[5]     cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non                                                                                                                                               
[6]     proident, sunt in culpa qui officia deserunt mollit anim id est laborum.  
```
