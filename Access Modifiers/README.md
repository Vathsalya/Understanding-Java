There are 4 access modifiers in java : 

1. public
2. private
3. protected
4. default

Create a java project in eclipse IDE. 

Create a package named 'base' and a package named 'one'.

Create a class named 'Base' in the 'base' package. Extend the Base class and create another class which is named as Child within the same package/folder as Base class(i.e., base package). Child class extends Base class. 

Create four parameters, one of each access modifier type.

Eg: 
class Base {
public String publicStringInBase;
private String privateStringInBase;
protected String protectedStringInBase;
String defaultStringInBase;
...
..
}


Similarly, create another package named 'one', create a class and name it 'ChildOne', ChildOne extends the Base class.

Create a package within the folder 'base' and name it 'two'. Create a class named 'Two' in package 'two'. Two extends Base class.


For each of the classes, created so far : Base, One and Two.

Create constructors and try to access each one of the fields in Base. 

Eg : 

class One extends Base{

One(){
this.publicStringInBase = "";
this.protectedStringInBase= "";
...
..

}

}


Use the content assist in eclipse (ctrl + space) to view the access permissions of fields within and outside the package. Observe how the behavior varies across public/private/protected/default member variables.






