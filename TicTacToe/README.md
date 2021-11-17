## Rewrite the following:

<b>1.</b> Rewrite this <i>switch statement</i> as an <i>if/else statement</i> and, if you can, use enumerated values to replace the magic numbers:

```cpp
int num = 1;

switch (num)
{
	case 0:
		std::cout << "0" << std::endl;
		break;
	case 1:
		std::cout << "1" << std::endl;
		break;
	case 2:
		std::cout << "2" << std::endl;
}
```

<b>2.</b> Rewrite this <i>if-statement</i> as a <i>switch statement</i> and remove the magic numbers in place of enumerations:
		
```cpp    
int age = 33;

if (age == 24)
{
	std::cout << "You are still very young!" << std::endl;
}
else if (age == 55)
{
	std::cout << "You are getting on in life" << std::endl;
}
else
{
	std::cout << "You are what you are..." << std::endl;
}
```

<b>3.</b> Rewrite this <i>for-loop</i> as a <i>while-loop</i>:
	
```cpp  
for (int i = 0; i < 10; i++)
{
	//insert your own action here...
}
```

<b>4.</b> Rewrite this <i>do-while</i> as a <i>for-loop</i>:

```cpp
int i = 0;
	
do
{
	//insert your own action here...
	++i;
} while (i < 25); 
```
