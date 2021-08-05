## JavaScript ##

### History of JavaScript

JavaCript is created by **Brendan Eich** in **1995** 

**Firstly** there **Microsoft** and **Apple**, Both system was too costly to use, then Netscape browser come. it was free so anyone can build the website on their own, and then they dont have to pay money to others.

**Netscape company become very big company in short time**, Microsoft wanted to buy that company but it get denied, then **microsoft** made own browser **internet exploler** and gave them free, because of this **netscape** market went down. At that time backend leader was **Java** of **Sun Microsystem**.
 
Java is always failed in front-end part so** Netscape Navigator** and **Sun Microsystem** came together and they wanted to fight **Microsoft**, then there was a developer called **Brandan Eich** who create language **Mocha** After that to make a proper name of **Netscape**, **LiveScript** and **Mocha** change their name to **Javascript**. 

In **1996**, **Google** started search Engines so they started using **Javascript**.The main business of Yahoo and Google was to make website. So they heavily contributing into JavaScript. So in **2009** **ES5** was finalized that all of the browsers started implementing **ES5**.  
In **2013** company noticed some drawbacks of **Javascript** so they changes that drawbacks and released new version in **2015** that is called **ES6**. 



----------


### JavaScript ###
- Javascript is text based programming language.
- It can be used for the client-side as well as server side. 
- It improve user experience of web page 
- We can say that javascript add behavior on web page, also it make web page interactive to user
- In **Javascript** everything is an **Object**.
- In **Javascript** **' + '** plus sign does Addition of number and Concatination of string
- In **Javascript** **' === '** It means Equal value and equal type
- In **Javascript** Type of **' null '** always return an Object. **etc...**


### ECMA Script ###
- Javascript is based on ECMAscript.
- It is also called as a Modern javascript<br>

**Version:**<br>
**ES5:**

- ES5 is stands for ECMAScript 5, also known as  JavaScript5, JScript5 and ECMA Script 2009
- It has only var keyword for defining variable.
- It has function Scope.

**ES6:**

- ES6 is stands for ECMAScript 6, also known as  JavaScript6, JScript6 and ECMA Script 2015
- It has let and const keyword for defining variable.
- It has block or Lexical Scope.
- Varios Browser supports ES5 and ES6.<br>
  **Eg.** Firefox, chrome **etc.**
 
**Also we have ES7, ES8……….**   


###Control Structure
- **if else:** Can be used for condition checking **If**(true condition takes place) **else** (false condition takes place)
- **for loop:** Block of code is executing till the condition is satisfied
- **switch case:** Better way available in javascript also it is a alternative of if-elseif-elseif-elseif........... <br>
Because in switch case **if** condition is matched then it terminate the loop.
- **while:** Block of code is executing till the condition is satisfied
- **do while:** Block of code is execute atleat one time till the condition is checked


### Operators  
- **Arithmetics:**	 +,  -,  * , / , % , ++ , -- , -= , *= , /= , == **Eg.** A+B
- **Assignment:**	 =, %= , -= , *= , /= , +=, **= **Eg.** (A/=B)
- **Comparision:**		<, >, =<, =>, ==, ===, != **Eg**. A > B
- **Logical:**		 &&, ||, ! **Eg.** A && B
- **Bitwise:**		 |, &, ~ **Eg.** A & B
- **ternary:**   	(**)?if :else  Eg. ((a+b === 1) ? c : d)  For Simple operation we can say it is an alternative of If-else

**For above all operation we want Operand and operator(Arithematic, Logical, Bitwise, ternary, assignment, comparision) mixture of operand and operator gives the result that is nothing but a what operater is does.**

### JavaScript Variables
- It is like containers, it can store any type of data <br>
  **Eg.** Array,object,int,float,number,null……….
- Javascript is a dynamic type variable, It means it decides variable type at runtime.
- It can be defines by using var, let and const keyword.


**Local Variable**

- It can be declared inside of any block.
- Once variable is defined in block or local scope it can not be accessible outside of block.
- If any updatation occur in method and property then it will not affect other function.
- It get terminated when function ends.<br>
**Eg.**
```
public int add(){
let a=7;
let b=10;
return a+b;	}
```


**Global Variable**

- It can be declare before start of any program.
- It can be accessible to rest of the program.
- If any updatation occur in method and prperty then it will  affect other function.
- It does terminated when other function ends.<br>
**Eg.**
```
var a=7;
var b=10;
public int add(){
return a+b;	}
```

**Lexical  scope**

- Lexical Scope is any block that is inside the functional Scope.
- It can access variable from outside of its block. Which is nearest to the lexical scope block.
- Lexical scope start with ‘{‘ ane end with ‘}’. <br>
  **Eg.** 
```
if(x){ let z = 7;    }
```		

**Functional Scope**

- It  means we can define variable more than one time again inside the function. 
- After running the programe defined variable goes on top due to hoisted.
- It can be local as well as global.
- It  starts with function f1(){ …….}		



### Identifiers
- If variables is identified with unique names then that is called identifiers.<br>
	**Eg.** var or let or const name, address,phone.

### Classification of Variable Data Types
There are two data types in JavaScript. It can hold any type of data<br>
        1. Primitive Datatype<br>
        2. Non-primitive data type

**1. Primitive data type**

- Once it is defined we can not change it, It means it wont be override.
- It can be used for holding of data. <br>
- There are five type of primitive data<br>
	- string  	**Eg.** let name=”Deepak”;<br>
	- Number	**Eg.** let mobile_no=1010101010;<br
	- boolean **Eg**. let a=true;<br>
	- undefined	**Eg.** let mobile_no; <br>
	- Null		**Eg.** let name=””;<br>
	- Symbol (it defined in ES6)<br>



**2. Non-Primitive data type**

- Once it is defined we can change it, It means it can be override.
- It can be used for hold large number of data at one place.
- Data can be in any type, It means either primitive or non-primitive.
- There are two type of non-primitive data.
	- Object {}	**Eg.**var obj = {key:"value"};
	- Array []		**Eg.**var arr = [7, 10, Null, true, [], {}];


### Differences in Var, Let and Const  variable ###

**Var**
 
- It defined in ES5.
- It can be redeclared.
- It can be reinitialized   
- It has a functional scope   
- It is dynamic type variable , so it get Hoisted.  
**Eg.**	var name = Deepak;  <br>
    	var name = "Sachin";    // It can override from Deepak to sachin


**Let**

- It defined in ES6.
- It can not be redeclared.
- It can be reinitialized, means we can assign value multiple time.
- It has a lexical scope
- It does not get hoisted.<br>
**Eg.1** let name = Deepak;  
    let name = "Sachin";    // It can not override because already taken before <br>
**Eg.2** let name = Deepak;  
    	name = "Sachin";    // re-initiliazed


**Const** 

- It defined in ES6.
- It can not be redeclared.
- It can not be reinitialized, means we can not assign value more than one time.
- It has a lexical scope
- It does not get hoisted.<br> 
**Eg.1** let name = Deepak;  
    let name = "Sachin";    // It can not override because already taken before<br>
**Eg.2** let name = Deepak;  
    	name = "Sachin";    // It can not re-initiliazed because already taken before.



**Var keyword** 

- It is defined in ES5.it has some drawback.
- It has functional scope so ‘var’ can be redeclared and reassign again and again . 
- So, In ES6 defined two variable 'let'  and ‘const’. it solved the issue of ‘var’ keywaord 
 
**Note:** Use **'let'** and **'const'** keyword for better understanding of program.



**Type casting**
- It convert any data type into other data type.<br>
**Eg.**<br>	
Var cost=77+3 			// output: 773		without type casting<br>
	Var cost=5+true			// output: 5true 	without type casting<br>
Var cost=number(“77+3”) 	// output: 80		with type casting

### Facts in javacript ###

Var n1=”[]” or “null” or “undefined” or “NaN” or “{}” or “Deepak” <br>
Anything which is in (“ “) is always a string in JavaScript.<br>
True=1<br>
False=0<br>
10+null=10<br>
10+7=107<br>
undefined + 10 = NaN  // (not a number)<br>
10 / null = NaN<br>
Null	// It is an object<br>
boolean(NaN or 0 or “ ” or  null or Undefined) = // output: false<br>

**(0, NaN, “ ” , null, Undefined) 	// All are falsy value<br>**




### Copy by Value And Copy by Reference ###
**Copy by Value**

- Anything that is pass by its Copy is called as call by value or copy by value in javascript.
- Copy of variable is used.
- All Primitive data types are copy by value. 
- Using  ‘=’ we can copy the value. <br>
 **Eg.**<br>
```
  var z = x + y;	console.log(z);
```    


**Copy by Reference**

- Location in memory of any variable, the variable don't actually contain the value it contain address that is called as call by reference or copy by reference .
- A variable itself is used.
- It holds the reference of the object.
- All Non-primitive values are call by reference.<br>
	**Eg.** Google docs, Excel sheet etc.



### Hoisting ###
- ‘Var’ variable it always get hoisted on top in fuctional scope only **'variable'** is hoisting not its value.
- At runtime **'variable'** are moves to the top that is nothing but a hoisting.
- **'let'** and **'const'** are not get hoisted because both can not be define more than one time

**Eg.1**
```
var x = 90;
    function f1(){
        x = 5; 	//hoisting      assign to a global var x		
 }
```   

**Eg.2**
```	x = 50;
	console.log(x); 		//output:50<br>
	var x; //here x can be hoisted
``` 

---


### Function ###
- It means a set of statements that perform a perticular task.
- It is like a container which store all type of data like primitive and non-primitive.
- It remain as it if there is no call of function, It can be call multiple time.
- It has functional, lexical, local and global scope.
- In ES5 function behaves like the same as variable.<br>
 **Eg.** Hoisting, overriding, scope.

### Why function is first class citizen in javascript###

- It can be reusable.
- It can be assign to a any variable
- It can acts as an object
- It can be return from function
- It can be used as pass by parameter
etc.....

**Eg.1 without parameter**<br>


	function f1(){	//defining function 
	} 

	f1();	//calling function


**Eg.2 with parameter**<br>

	const f1 = function(a,b){ //defining function as a parameter
    
	const c = a + b;
	}
	f1(5,10); //calling function as a parameter



**Anonymous function**
- It means a function that does not have a name.<br> 

    var f1 = function(){
	    console.log("Anonymous");
    }
    f1();


**Function Declaration**

- It defines a function with function name.
- It start with function function_name, it can be parameter and non parameter.
- It can be hoisted 
      
      	function function_name(){
    	console.log("Function Declaration");
    	}
        
      
**Function Assignment**

- It means a function is assign on any variable can be var, let and const.
- variable name will be the the function name where it assigned
- It can not be hoisted.
- Anonymous Function cab be a assignment function.


       	var function_name = function() {
            console.log();   
        	}
     

**Cascading function**

- It means in function more than one function takes place.
- Remaining function are part or child of main function .


		f1(){
			console.log(); }
		f2(){
			console.log(); }
		f3(){
			console.log(); }
		f1()()();
	

### Inline Function ###

- A Function can be defined within a function is called inline function
- It can be a type of private function.
- It can be a type of higher order function
   
   		function f1(param){
		console.log();
		}(function(param){ //Inline function
			console.log();
		});
    


### Higher Order Function

- A function which take function as a parameter or it can return any function that is called as High order function.
- It can be as a type of First class citizen. 

   		function f1(param) {
        const name = "Deepak";

        function f2(param) {
            console.log(param,name); 
        }
        return f2(param);
	    }
    
		f1(7); 



### Pure Function ###
 
- A function in which, whatever we have passed only that value is returning.
- If parameter is not modified then that function will be pure function.


		function f1(a,b) {
    	return a*b;
		}
		f1(7,10);




### IIFE

- It Stands for **Immediately Invoked Function Expression**.
- It means defining and calling of function at a same time.
- It can be a type of anonymous function.
- It can be a type of private function.
- It can be called only once.

	
		(function(){   
		console.log();
		})();   //calling IIFE function
	
   

### Arrow Function ###

- It is a part of ECMAScript 6.
- '()==>' This is using instead of function.
- It can be an alternative of function assignment. 
- It is always be function assignment not function declaration.


	
		let a = () => { code }

		const b = (x,y)=> { code }



### JavaScript Constructor And Prototype ###

- A constructor is a function, When we use a new keyword it becomes the object constructor. 
- Function is an object prototype in javascript. 
- Object is derived from object prototype, object is constructor.
- object prototype itself is derived from prototype  object.
- so now we can say that javascript is based on object.

**Prototypes**

- Array
- Object
- Function
- String
- Boolean
- Number
- RegExp
- Date
- Math


 
**Date**

- It returns the date like day, month, year.<br>
**Eg.** getDate(), getHours(), getMonth(),getMinutes() etc.

**Math**

- It is used for mathematical operation.<br>
**Eg.** random(), floor(), max(), min(), sqrt(),etc.


**Note:**
- Function is inside an object is called method
- Array index-based object.
- using array we can read the data of array

	let data{"name":Deepak, "location":Mumbai, "f1":function() }  
	 "f1":function() //method



### Array Methods ###

- **push** - add element at the end
- **pop** - remove element from end
- **forEach** - acts as a for loop,
- **map** - map the element in array, It return the length of an array
- **filter** - filter element from array
- **indexOf** - return the index of element
- **includes** - returns true if values exists otherwise return false
- **concat** - concate element
- **join** - it join array element to some value
- **length**	It returns length of the array.   

### Object Methods ###

- **toString** - convert data into string data can be Primitive nad non primitive
- **valueOf** - Return value of key
- **freeze** - It is used to freeze the object. It will not change after freezing it
- **assign** - It creates a new object and assigns it to the new object.   |
- **isArray** - It returns true if data is array else false.

### String Methods ###

- **toUpperCase** - convert string into uppercase letters
- **toLowerCase** - convert string into lowercase letters
- **split** - separates value of string and return array
- **join** - join all array elements and return string
- **replace** - replace the value, old element to new element.
- **trim** - remove extra space from both the edges of any data
- **substring** -subtracting the string.



### Built-In Functions In JavaScript ###
                           
- setTimeOut()- It delay the execution of code. It runs only once
- setInterval()- It continue excute code till clearInterval clear the time
- clearInterval()- It clear the interval time from code 
- parseInt()- It converts any number into an integer value. 
- parseFloat()- It converts a number into a floating-point number

**Eg.1**

		setTimeout(function()
		{ console.log("i will print after 5 secs"); },
		 5000);

**Eg.2**

		var x = setInterval(function()
		{ console.log("i will countinue print after 5 secs"); },
		 5000);

		clearInterval(x); // It will clear the interval when it call

### JSON ###
 
- It stands for Javascript object notation.
- It can be used for tranfer and recieve data from one application to another application.
- It contains data in terms of key value pair.
- JSON data are always stored in double Qoute " ".
-  It has two method for transfer and recieve data 
- JSON.stringify(obj)
- JSON.Parse(Obj);<br>
**Eg.**

        const send_data = JSON.stringify(x);// Used for sending data

        const recieve_data = JSON.parse(send_data);// use for receiving data















