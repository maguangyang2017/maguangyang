 ```
 ● 面向对象录入信息：
  ● import java.until.Scanner;
public class Demo{
Static Student	[] students=new Student[100]
Static Scanner sc = new Scanner(System.in);
public static void main(String[] args){
printMenu();
}
public static void printMenu(){
System.out.println(选择数字);
System.out.println(1.增加);
int flag = sc.nextInt;
switch(flag){
case 1: 
addStudent();
break;
default:
printMenu();
}
}
public static void addStudent(){
int i=0;
boolen isCome=true
//while(isCome){
System.out.println(请输入学生名);
String name = sc.next;
Student student = new Student(name,age,sex)
students[i]  = student;
i++;
for(Student s:student){
if(s!=null){
s.say();
}
}
}
printMenu();
}


}
public static void selectStudent(){
System.out.println(请输入学生名);
int flag = sc.nextInt;
for(Student s:students){自己判断数组长度==int =0 i<student.length;i++
                                                       student s[].say();
if(s!=null){
s.say();
}
}
printMenu();
}
  ● private  int age;   不能更改年龄
  ● 用get/set访问私有成员，有可控性； 
只要用了private就只能在本方法体中使用，在外部访问就必须使用get/set方法。
```
