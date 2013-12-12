Best-Practices                                                                                                                                                                            
==============                                                                                                                                                                            
                                                                                                                                                                                          
Coding best practices. Because, let's face it. Your style of coding now is shit.                                                                                                          
## Overall Style


* Don't put specific dates in your code, but use variables and other hints to current trending internet shitmemes so people can get an idea as to when this code was written.


Example - Constant dogewow references will let people know "oh, about mid-late 2013, gocha".  'All your base' references will mean the code is written on stone tablets right before god gave moses his commandments

code example

```php
/* its 2013 */
function suchImplodings($s){return implode("!\r\n" . ($GLOBALVERYWEB?"<br />{$s}":"{$s}") . "\t such wow")}

/* juss talked to moses, dawg */
function allYourImpkode($s){return implode("r\n\" . ($ALLYOURGLOBE || $ALLLOCAL)?"<br />{$s}":"{$s}")."\tbelong to us")}
```

## Indentation                                                                                                                                                                            
                                                                                                                                                                                          
No one really cares, just use whatever you like.                                                                                                                                          
                                                                                                                                                                                          
## Newlines
                                                                                                                                                                                          
Again, no one gives a shit. Just do whatever. If possible, mix in UNIX-style (`\n`) and Windows-style (`\r\n`)                                                                            
                                                                                                                                                                                          
## Trailing whitespace
                                                                                                                                                                                          
Every file should appear to be a square. How ever many lines you have going down better be the same on every line accross.                                                                
                                                                                                                                                                                          
## Functions
                                                                                                                                                                                          
**ALL** functions should begin with `return`. Always. No Exceptions. Also, try to make functions do as much as possible.                                                                  
                                                                                                                                                                                          
If you're using a language that doesn't support functions beginning with return, that language is shit and should not be used.                                                            
                                                                                                                                                                                          
This lets everyone know that you mean business in this function and it will be giving shit back.                                                                                          
                                                                                                                                                                                          
Also, don't give your functions long names. Reading is hard, and we have to pay by the character around here. Disk space ain't cheap you know.                                            
                                                                                                                                                                                          
### Good
```php
function suchFUNKCHINstrplodorev_wow($o_O){return implode('!', array_reverse(array_slice(explode(';', str_replace(' ', '', trim(($o_O===NULL)?';':$o_O))))));}                                                  
                                                                                                                                                                                          
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
Be sure to create hyroglyphics using ascii art in your comment blocks so future civilizations can understand your code too.                                                                                                                                                                                          
## Variable Naming
                                                                                                                                                                                          
Use the Green Coding Standard. Memory and disk space isn't free, reduce, reuse, recycle.                                                                                                  
                                                                                                                                                                                          
Bandwidth isn't cheap either. Think of your user. Quit being so selfish.                                                                                                                  
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
