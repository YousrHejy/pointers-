Const is used for:

1.	Constant Variables
Ex: 
const int x=5;
•	The value of x won’t change throughout the whole program 
•	Any trial to change this variable will lead to an error

2.  constant function Declaration
const void push(){
 // function
}
•	Push() can’t modify the object in which it is called.

3. const return type 
const void push(){
 //code of the function
}
int main (){
push(5)
}

4. A pointer that points to a const value
Ex: 
int var=5;
const int *ptr=&var;
•	Ptr cannot change the value of var.  

5.  const pointer to the data
int *const ptr=&var;
•	ptr cannot change the address it’s holding. 

6. constant pointer to const data 
Const int *const ptr= &var;
•	ptr can neither change the address it’s pointing to nor change the value of var.


7. Const function parameters
void print(const int y){
cout<<y<<endl;
}





& Used for:

1. Address operator yields a pointer to its operand.
Ptr=&y;

2.	A reference declarator in addition to being the address operator.

3.	Logical AND
int main (){
int x=7,y=4;
cout<<x&&y<<endl;
return 0;
}
•	Output will be 1 (true)
•	while if x=0 and y=4, the output will be 0 (false)
 

4.	Bitwise AND
int main (){
int x=1,y=5;
cout<< x&y <<endl;
}
•	The output will be 1
