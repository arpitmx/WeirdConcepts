# SomeWeirdConceptsLanguages

## Python

### 1 : The weird 'is' :

a = 256
b = 256 
a is b

output: True

but 

a = 257
b = 257
a is b 

output: False

Why ?

> 'is' is for comparing the ids of two given datatypes. 
if id(a) == id(b) then it returns true else false.

QUE: why with a=256 one it was true ? 

> python makes a array of integers in range of -5 to 256 in its memory during initialization , so when we call '256 is 256' its actually 
> comparing the ids of the object of same array therefore it's true...
> and when we compare in with 257 , as it is not in the initialized array new and UNIQUE ids will be given to each objects when initialized , therefore , false.



=========================================================================================
