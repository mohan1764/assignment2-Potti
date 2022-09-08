# assignment2-Potti
# Mohan Varasiddhi Sai Potti
## my favourite museum is Government museum Chennai
The Government Museum in **chennai** is the second oldest museum in **India**.

***
# Ordered list
## chennai international airport is near to Government museum 
1. chennai international airport
    1. terminal departure
    2. came out from the airport
2. booking cab 
    1. cab came 
    2. entered into the cab
3. reached government museum 
    1. buying entry ticket
    2. entering into museum

* samosa point
    * green chutney
    * sauce
* metro park
    * view
    * entertainment
* pheonix mall
    * play zone
    * barbequenation
    * clothes

[link to aboutme](AboutMe.md)



***
# Table
The following table describes famous cities everyone must visit 
|Name of city|Important location|Time      |
|:----------:|:----------------:|:--------:|
| Guntur     | Mirchi yard      | 4 hours  |
| vijayawada | Pvp square       | 6 hours  |
| Hyderabad  | Brabd Factory    | 8 hours  |
| Delhi      | Momos hub        | 8 hours  |


***
# quotes
> "It is a far, far better thing that I do, than I have ever done; it is a far, far better rest I go to than I have ever known". 
> Author: *A.p.J Abdul Kalam*

> "Kill them with your success, bury them with your smile".
> Author: *Divya*

> "Trust no one, kill anyone, be only one".
> Author: *Prabhas*

***
# Fencing
>This is a simple JavaScript helper which allow you darken or lighten a colors in your application. This function takes colors in hex format (i.e. #F06D06, with or without hash) and lightens or darkens them with a value. Quick link to script<https://www.npmjs.com/package/lighten-darken-color>

```
function LightenDarkenColor(col, amt) {
  
    var usePound = false;
  
    if (col[0] == "#") {
        col = col.slice(1);
        usePound = true;
    }
 
    var num = parseInt(col,16);
 
    var r = (num >> 16) + amt;
 
    if (r > 255) r = 255;
    else if  (r < 0) r = 0;
 
    var b = ((num >> 8) & 0x00FF) + amt;
 
    if (b > 255) b = 255;
    else if  (b < 0) b = 0;
 
    var g = (num & 0x0000FF) + amt;
 
    if (g > 255) g = 255;
    else if (g < 0) g = 0;
 
    return (usePound?"#":"") + (g | (b << 8) | (r << 16)).toString(16);
  
}
// Lighten
var NewColor = LightenDarkenColor("#F06D06", 20); 

// Darken
var NewColor = LightenDarkenColor("#F06D06", -20); 
```

Quick link to snippet<https://css-tricks.com/snippets/javascript/lighten-darken-color>