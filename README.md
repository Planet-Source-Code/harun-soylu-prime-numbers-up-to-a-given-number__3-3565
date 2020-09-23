<div align="center">

## Prime numbers up to a given number


</div>

### Description

This code prints the prime numbers to the screen up to a given number, and also find out if the given number is prime or not.
 
### More Info
 
This program read an integer value from the keyboard and print out all prime numbers that has an upper limit of input. I use four for loop to find and print all the numbers. This is my first program on this web-side I use linux platform to edit and compile and there is no error. If you have any questions or suggestions about the program please do not hesitate to contact with me.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Harun Soylu](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/harun-soylu.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |C
**Category**       |[Math](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math__3-12.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/harun-soylu-prime-numbers-up-to-a-given-number__3-3565/archive/master.zip)





### Source Code

```
#include "stdio.h"
int main(){
	int i,j,a,control=0,control2=0;
	printf("\nPlease write a number...");
	scanf("%d",&a);
	for(i=2;i<a;i++){
		for(j=2;j<i;j++){
			if(i%j==0){
				control2++;
				}
		}
			if(control2==0)
				printf("%d\n",i);
			if(a%i==0){
			control++;
			}
			control2=0;
	}
	if(control==0)
     	printf("\n%d is prime \n",a);
	else
		printf("\n%d is not prime\n",a);
		return 0;
}
```

