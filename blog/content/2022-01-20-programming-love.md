+++
title = "Programming Love"
description = "Its a bug story, baby just say"
+++

One day a user of the programmer's program, programmed in a programmable program programmed to program programs, came up to a fellow programmer with a bug that they had to resolve.

"*the foo module is broken, and the code involving its logic is too*
*complicated for me to understand*"  
**Gives**
>  - α Line
>  - β Line
>  - γ Line
 
**Expected**     
>   - γ Line
>   - β Line
>   - α Line


The fellow programmer after hearing this, 
asked the questioning programmer to add these lines
to the codebase immediately after the file is closed.

```ruby
#
# convoluted logic that does the does the actual
# file writing 
... 
lines = open(the_file_that_was_written, 'r').readlines()
open(the_file_that_was_written, 'w').writelines(lines.reverse())
```

The Questioning Programmer was happy to see this thing work and went on to enjoy their free time.  
The fellow Programmer wrote a note to self on how this approach of fixing bugs is better.  
Here's an excerpt from their wisdom.
> * It avoids you the pain of going through horrible lines of program someone else wrote (ofc, its always someone else who writes stupid things).
> *  We Programmers program, not read.  

They published their whole agenda as a manual in a [github repo](https://www.github.com/pwltp/agenda)[^1]


**P.S**: A week later, devops team is debugging random restart of pods.

**********************************
#### Refs
[^1]: Yes, I'm aware it points to a non existant url(at the time of writing)  
