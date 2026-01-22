## experiment 3
## TITLE : constructor overloading in java
```
class Student {

    String name;
    int age;
    int marks;
    Student() {
        name = "Not Assigned";
        age = 0;
        marks = 0;
    }
    Student(String n, int a) {
        name = n;
        age = a;
        marks = 0;
    }
    Student(String n, int a, int m) {
        name = n;
        age = a;
        marks = m;
    }
    void display() {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Marks: " + marks);
    }
    public static void main(String[] args) {

        Student s1 = new Student();                 
        Student s2 = new Student("Alice", 20);
        Student s3 = new Student("Bob", 22, 90);  

        s1.display();
        s2.display();
        s3.display();
    }
}
```
## output
![output of screenshot](3a.output.png)
