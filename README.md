# EXP:08 Using-Inheritance-one-class-can-acquire-the-properties-of-others
# Program
```
Developed By : Vishal Gowthaman K R
Reg No : 212221230123
```
```
class Parent {
    int parentProperty;

    void parentMethod() {
        System.out.println("Parent's method");
    }
}

class Child extends Parent {
    int childProperty;

    void childMethod() {
        System.out.println("Child's method");
    }
}

public class InheritanceExample {
    public static void main(String[] args) {
        Child childObj = new Child();
        childObj.parentProperty = 10;
        childObj.childProperty = 20;
        
        System.out.println("Parent Property: " + childObj.parentProperty);
        System.out.println("Child Property: " + childObj.childProperty);
        
        childObj.parentMethod();
        childObj.childMethod();
    }
}

```
# Output
![image](https://github.com/Rohith-AIDS/Using-Inheritance-one-class-can-acquire-the-properties-of-others/assets/94980736/f951ded0-bd56-4534-9c53-2d2dc60e18b2)
