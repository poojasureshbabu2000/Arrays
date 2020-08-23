# Arrays
How To Create An Array Of Objects In Java?
An array of objects is created using the ‘Object’ class.

The following statement creates an Array of Objects.

Class_name [] objArray;
Alternatively, you can also declare an Array of Objects as shown below:

Class_nameobjArray[];
Both the above declarations imply that objArray is an array of objects.

So, if you have a class ‘Employee’ then you can create an array of Employee objects as given below:

Employee[] empObjects; 
OR
Employee empObjects[];
The declarations of the array of objects above will need to be instantiated using ‘new’ before being used in the program.

You can declare and instantiate the array of objects as shown below:

Employee[] empObjects = new Employee[2];
Note that once an array of objects is instantiated like above, the individual elements of the array of objects need to be created using new.

The above statement will create an array of objects ‘empObjects’ with 2 elements/object references.
