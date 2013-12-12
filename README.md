Best-Practices                                                                                                                                                                            
==============                                                                                                                                                                            
                                                                                                                                                                                          
Coding best practices. Because despite all your efforts you still can't seem to get it right. Your style of coding now is shit.                                               

## Overall Style


* Don't put specific dates in your code, but use variables and other hints to current trending internet shitmemes so people can get an idea as to when this code was written.


Example - Constant dogewow references will let people know "oh, about mid-late 2013, gocha".  'All your base' references will mean the code is written on stone tablets right before god gave moses his commandments

code example

```php
/* its 2013 */
function suchImplodings($s){return implode("!\r\n".($GLOBALVERYWEB?"<br />{$s}":"{$s}")."\t such wow")}

/* juss talked to moses, dawg */
function allYourImpkode($s){return implode("\r\n".($ALLYOURGLOBE||$ALLLOCAL)?"<br />{$s}":"{$s}")."\tbelong to us")}
```

## Indentation                                                                                                                                                                            
                                                                                                                                                                                          
No one really cares, just use whatever you like.                                                                                                                                          
                                                                                                                                                                                          
## Newlines
                                                                                                                                                                                          
Again, no one gives a shit. Just do whatever. If possible, mix in UNIX-style (`\n`) and Windows-style (`\r\n`)                                                                            
                                                                                                                                                                                          
## Trailing whitespace

Nothing is more aggrivating to programmers 
as when pressing the <down arrow> key the cursor 
moves to the end of the line below, because that line isn't as 
long as the one above it.  Put enough white space after every 
line so when I move my cursor down, it goes down, not wherever 
it wants to go.

* Make sure empty 'white space' lines also include enough spaces to prevent 'cursor position hijacking'

Every file should appear to be a square. How ever many lines you have going down better be the same on every line accross.                                                                
                                                                                                                                                                                          
## Functions
                                                                                                                                                                                          
**ALL** functions should begin with `return`. Always. No Exceptions. Also, try to make functions do as much as possible.                                                                  

This lets everyone know that you mean business in this function and it will be giving shit back.                       
                                                                                                                                                                                          
If you're using a language that doesn't support functions beginning with return, that language is shit and should not be used.                                                            
                                                                                                                                                                                          
Also, don't give your functions long names. Reading is hard, and we have to pay by the character around here. Cloud Storage ain't cheap you know.

Ideally, functions will obliterate the values passed to them when they're finished. This will help avoid memory leaks.
                                                                                                                                                                                          
### Good
```php
function suchFUNKCHINstrplodorev_wow($o_O){return implode('!',array_reverse(array_slice(explode(';',str_replace(' ','',trim(($o_O===NULL)?';':$o_O))))));}                                                  
                                                                                                                                                                                          
```                                                                                                                                                                                       
                                                                                                                                                                                          
### Bad
```php                                                                                                                  
function stringManipulationExample ($str) {
  $strReturn = '';
  $strReturn = str_replace(' ', '', $str);
  /* fuck this garbage code. You get the picture. */
```                                                                                                                                                                                       
                                                                                                                                                                                          
## Helper Functions
                                                                                                                                                                                          
Don't use them. Too many functions make your code harder to process and read. And reading is **hard**. If possible, copy paste code around as much as possible. If necessary make is as specific as you can to its current context.

Ideally do not use them at all.
                                                                                                                                                                                          
## Variables                                                                                                                                                                              
                                                                                                                                                                                          
Don't create unnecessary variables that you won't use more than once. Just because memory is cheap doesn't mean you get to abuse it, it's not a whore. Have some respect fot your users.  
                                                                                                                                                                                          
                                                                                                                                                                                          
When possible, manipulate global variables and pass by reference.                                                                                                                         



## Variable Names

Before you start your project, calculate
approximately how many different variables you're going to
use.  Divide that number by 26.  Round up.  However many you
get, that is the character length of your variable set.

For example: if the number is 3, your first variable is `$aaa`

The next is `$aab`

Use an excel spreadsheet to keep track of your variables, and make sure to include it in the source code

That way everyone knows exactly where `$axf` goes, vs `$asf`

When your program blows up, it might tell you which variable it choked on, and then you don't have to guess where that is.                                                  

**Note:** Virus scanners look for common hacker variables like `'tmpStr'`
and `'strInput'`, using the variable spreadsheet will avoid your
code getting flagged as a virus


## Classes                                                                                                                                                                                
They're good for learning programming.

*Real* programmers don't need them.

Classes are good for learning, but once you have all your classes, you don't need them anymore.
                         
**Don't** write professional code while in a class, because you're still learning obviously

> (aka DURR I DONT KNOW WHAT A CLASS IS LAWLS)

> OOP === OTHER PPLZ PROPERTIEZ                                                                                                                                               


## Built in functions
                                                                                                                                                                                          
When possible, override them with shorter names. You're better than those yahoos who wrote whatever language you're using, quit kidding yourself.                                         
                                                                                                                        

*Good -- Array is destroyed as we look through it*
```php

/*check if a contained v*/
function ct(&$a, $v){return ($a)?($a[0]===$v)?TRUE:($a[0]==$v)?TRUE:ct(array_splice($a,1),$v):FALSE;}
```
*Bad -- Array is preserved. We could maybe sometime almost start to have a memory leak*
```php
/*check if a contains v*/
function ct(&$a, $v){return ($a)?($a[0]===$v)?TRUE:($a[0]==$v)?TRUE:ct(array_slice($a,1),$v):FALSE;}
```

## Commenting
                                                                                                                                                                                          
***ALWAYS*** use `/* */` style comments. It's easier to read for my IDE. It's best to just not comment anything though.                                                                   
Be sure to create hyroglyphics using ascii art in your comment blocks so future civilizations can understand your code too.                                                                                                                                                                                          
## Variable Naming
                                                                                                                                                                                          
Use the Green Coding Standard. Memory and disk space isn't free, reduce, reuse, recycle.                                                                                                  
                                                                                                                                                                                          
Bandwidth isn't cheap either. Think of your user. Quit being so selfish.                                                                                                                  
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
## Final Thoughts                                

If you can write a functional program beyond
the complexity of a 'hello world' using these standards, then
you have truly the a whole master programmer                                                                                                                                       
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
                                                                                                                                                                                          
