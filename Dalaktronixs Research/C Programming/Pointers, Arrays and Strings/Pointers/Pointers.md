* Pointers are Variable which stores the address of another referenced variable. 
* Pointers Are designated with an * to differentiate it from normal Variable
	* int \*ptr; //Pointer Declaration
	* int ptr; //Wrong Pointer Declaration 
* Declaration and Initialization Method
	* Pointers can be declared and Initialized on a single line code
	* int \*ptr = &a;
		* The ptr stores address of the referenced variable **a** 
	* Pointer Declaration and intialization can be done a different line of codes
		* int \*ptr; //Declaration
		* ptr = &a; //Initialization
* Important Question:
	* Can Pointer be assigned values; \*ptr = 5; 
* ### Types of Pointers
	* Normal Pointer
	* Null Pointer
	* Generic or Void Pointer
	* Wild Pointer 
		* These are initialized pointers
	* Pointers to Array
		* **type (\*pointer_name) \[SIZE]**
		* **char (\*x)\[6] = {1, 2, 3, 4 }**
	* Pointer of Pointers
	* ![[PointersinC.png]]
	* Pointers to Structures 
	* Pointers to String
	* Pointers to Function