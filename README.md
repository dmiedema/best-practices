Best-Practices                                                                                                                                                                            
==============                                                                                                                                                                            
                                                                                                                                                                                          
Coding best practices. Because, let's face it. Your style of coding now is shit.                                                                                                          
                                                                                                                                                                                          
## Indentation                                                                                                                                                                            
                                                                                                                                                                                          
No one really cares, just use whatever you like.                                                                                                                                          
                                                                                                                                                                                          
## Newlines
                                                                                                                                                                                          
Again, no one gives a shit. Just do whatever. If possible, mix in UNIX-style (`\n`) and Windows-style (`\r\n`)                                                                            
                                                                                                                                                                                          
## Trailing whitespace
                                                                                                                                                                                          
Every file should appear to be a square. How ever many lines you have going down better be the same on every line accross.                                                                
                                                                                                                                                                                          
## Functions
                                                                                                                                                                                          
**ALL** functions should begin with `return`. Always. No Exceptions. Also, try to make functions do as much as possible.                                                                  
                                                                                                                                                                                          
This lets everyone know that you mean business in this function and it will be giving shit back.                                                                                          
                                                                                                                                                                                          
Also, don't give your functions long names. Reading is hard, and we have to pay by the character around here. Disk space ain't cheap you know.                                            
                                                                                                                                                                                          
### Good
```php
function strplodorev($s){return implode('!', array_reverse(array_slice(explode(';', str_replace(' ', '', trim(($s===NULL)?';':$s))))));}                                                  
                                                                                                                                                                                          
```                                                                                                                                                                                       
                                                                                                                                                                                          
### Bad
```                                                                                                                                                                                       
                                                                                                                                                                                          
```                                                                                                                                                                                       
                                                                                                                                                                                          
## Helper Functions
                                                                                                                                                                                          
Don't use them. If possible, copy paste code around as much as possible. If necessary make is as specific as you can to its current context.                                              
                                                                                                                                                                                          
## Variables                                                                                                                                                                              
                                                                                                                                                                                          
Don't create unnecessary variables that you won't use more than once. Just because memory is cheap doesn't mean you get to abuse it, it's not a whore. Have some respect fot your users.  
                                                                                                                                                                                          
                                                                                                                                                                                          
When possible, manipulate global variables and pass by reference.                                                                                                                         
                                                                                                                                                                                          
## Classes                                                                                                                                                                                
                                                                                                                                                                                          
They're good for learning programming.
                                                                                                                                                                                          
## Built in functions
                                                                                                                                                                                          
When possible, override them with shorter names. You're better than those yahoos who wrote whatever language you're using, quit kidding yourself.                                         
                                                                                                                                                                                          
```php
/*check if a contains v*/
function ct(&$a, $v) {return ($a)?($a[0]===$v)?TRUE:ct(array_slice($a,1),$v):FALSE;}                                                                                                      
                                                                                                                                                                                          
```
                                                                                                                                                                                          
## Commenting
                                                                                                                                                                                          
***ALWAYS*** use `/* */` style comments. It's easier to read for my IDE. It's best to just not comment anything though.                                                                   
                                                                                                                                                                                          
## Variable Naming
                                                                                                                                                                                          
Use the Green Coding Standard. Memory and disk space isn't free, reduce, reuse, recycle.                                                                                                  
                                                                                                                                                                                          
Bandwidth isn't cheap either. Think of your user. Quit being so selfish.                                                                                                                  
                                                                                                                                                                                          
