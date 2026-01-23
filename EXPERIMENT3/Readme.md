# EXPERIMENT3
## TITLE:3A.)implement constructor over loading in java
```
class Student {

	String name;
	int age;
	double marks;

	Student() {

	}

	Student(String name, int age, double marks) {

		this.name=name;
		this.age=age;
		this.marks=marks;

	}

	void display() {

		System.out.println("Name: "+name);
		System.out.println("Age: "+age);
		System.out.println("marks: "+marks);

	}
}
MAIN.JAVA

 class Main {

	public static void main(String args[]) {

		Student std = new Student();
		std.display();

		Student std1 = new Student("Hari", 40, 67.8);
		std1.display();

	}
}
```
# output
<img width="162" height="148" alt="3a output" src="https://github.com/user-attachments/assets/4e34c018-e9b8-4a20-bf49-efed61702f2c" />
