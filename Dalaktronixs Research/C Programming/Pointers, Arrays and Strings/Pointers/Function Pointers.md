### Declaration Syntax

- [ ] Single Function Pointer Prototype
- [ ] Arrays of Functions 
- [ ] As Wrapper for Multiple Functions 

* Standard Function In C
	* int sum (int a, int b)
	* conversion to Function Pointers
		* `type (*funcPointer)(argument, ...)`
		* ```c int (*func)(int, int)``` 
* Arrays of Function Declaration
	* `type (*funcPointer[ ])(argument type list, ....) = {func1, func2, func3 ....}`
	* `double (*func[ ])(double, double) = {func1, func2, func3 ....}`
	* 