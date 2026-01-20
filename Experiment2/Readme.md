# EXPERIMENT 2
## TITLE : 2a.) Implementing class mechanism in java
```
class square {
  int length;
  int areaofsquare(){
     return length*length;
  }
  int perimeterofsquare(){
     return 4*length;
  }
}
class main {
  public static void main(String arg[]){
  square sq=new square();
  sq.length=5;
  int area = sq.areaofsquare();
  int perimeter = sq.perimeterofsquare();
  System.out.println("area of square:"+area);
  System.out.println("perimeter of square:"+perimeter);
  }
}
```
# OUTPUT
![output of class mechanism in java](2a.PNG)

## TITLE :2b.) Implement method overloading in java
```
class add{
 int add(int a,int b){
   return a+b;
 }
 double add(double a,double b){
   return a+b;
 }
 int add(int a,int b,int c){
   return a+b+c;
 }
}
class main{
 public static void main(String arg[]){
   add a=new add();
   System.out.println("addition of two integer:"+a.add(5,6));
   System.out.println("addition of real numbers:"+a.add(3.5,6.7));
   System.out.println("addition of three inters:"+a.add(7,6,5));
 }
}
```
# OUTPUT
![output of overloading in java](exp2b.PNG)

## TITLE :2c.) Implement class customer in java
```
class student{
 String name;
 int age;
 double marks;
 student(String n,int a,double m){
   name = n;
   age = a;
   marks=m;
 }
 void display(){
   System.out.println("student name:"+name);
   System.out.println("student age:"+age);
   System.out.println("student marks:"+marks);
 }
}
class main{
  public static void main(String arg[]){
    student std=new student("pavani",22,98.6);
    std.display();
  }
}
```
![output of customer in java](exp2c.PNG)

