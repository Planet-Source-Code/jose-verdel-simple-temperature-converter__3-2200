<div align="center">

## Simple Temperature Converter


</div>

### Description

Coverts Celsius temperatures to Fahrenheit and visa versa.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jose Verdel](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jose-verdel.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |C\+\+ \(general\), Borland C\+\+
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__3-1.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jose-verdel-simple-temperature-converter__3-2200/archive/master.zip)





### Source Code

```
//////////////////////////////////////////////////
Simple Temperature Converter (c) Jose Verdel 2001
//////////////////////////////////////////////////
#include <iostream.h>
int main()
{
	char temp_t;
 float temp;
 cout << "Enter temperature to be converted:";
 cin >> temp;
 cout >> "Enter f if temperature is Fahrenheit or c for Celsius:";
 cin >> temp_t;
 if (temp_t == 'f')
 {
cout <<"\nThe Celsius temperature is:" << (5.0 / 9.0) * (temp -32.0) << endl;
 }
 else
 {
cout <<"\nThe fahrenheit temperature is:"   << (9.0 / 5.0) *( temp + 32.0) <<endl;
 }
 return 0;
}
```

