# Dileep Sumanth Yarajala
He’s got a head on his shoulders The perfect guy is smart. There are no two ways about it.

![My Photo](/Sumanth.jpg)

---
# Goa trip
Let’s quickly have a look at the best places to visit in Goa with your friends 1. Calangute Beach Also known as the queen of beaches, Calangute Beach is one of the top-notch attractions to visit when you are planning your trip with your friends. The beach is known for the number of watersports and shacks.

|**Country**      |    **Reason for visit**     |    **Number of days** |
|-----------------|-----------------------------|-----------------------|
| Saudi           |  Vaccation                  |       24              |
| Japan           |  Family Function            |       12              |
| China           |  Holiday                    |       06              |   
| Lambasingi      |  Vaccation                  |       30              |

---

**Pithy quotes**

> There’s just something about getting a good laugh in that can make your day a million times better. If you’re looking for funny quotes to make you smile, to give a toast with, or to send to a loved one, you’ve come to the right place. -_Chethan_-
> 
> Love is messy, weird, difficult and oftentimes very funny. These funny love quotes are the most relatable thing you’ll read all day. -_Sumanth_

# Code Fencing

> [How to use string.replace() in python 3.x](https://stackoverflow.com/questions/9452108/how-to-use-string-replace-in-python-3-x#:~:text=str.replace%20%28old%2C%20new%20%20%20count%5D%29%20Return%20a,given%2C%20only%20the%20first%20count%20occurrences%20are%20replaced.)

Sass
```
@function str-replace($string, $search, $replace: '') {
  $index: str-index($string, $search);
  
  @if $index {
    @return str-slice($string, 1, $index - 1) + $replace + str-replace(str-slice($string, $index + str-length($search)), $search, $replace);
  }
  
  @return $string;
}
```
[Str-replace Function](https://css-tricks.com/snippets/sass/str-replace-function)