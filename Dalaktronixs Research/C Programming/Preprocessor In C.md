Preprocessing is the top step for compilation of a C code. Processing however, does the following actions.
* **Preprocessing Stage Actions**
	* It includes source code of included libraries
	* It removes all comments from the Source Code 
	* It replaces all macro definition by it values
* Preprocessors in C and C++ are characterized by the # tag which denotes **Preprocessor Directives** 
* The Preprocessor is Divided into the following types
	* File or library Inclusion **#include**
	* Conditional Compilation: **\#if,  \#elif,  \#else,  \#endif,  \#ifndef**
	* Pragma Directives
	* Macro Definition **\#define**
* **Include Guards in Preprocessor**
	* The include guards are used to prevent double inclusion of header files or libraries in C or C++
	* Syntax 
		* \#ifndef \_FILENAME_H_
		* \#define \_FILENAME_H_
		* 