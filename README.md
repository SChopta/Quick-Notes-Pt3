# Quick-Notes-Pt3
Classes, Objects, Methods

package project1;
class Person {
	//Instance variables (data or "state")
	String name;
	int age;
	
	/* Classes can contain
	1. Data (characteristics of object)
	2. Subroutines (methods)
	*/
	
	void speak() { //this is a method(added to class) you need to add code to call this method
		System.out.println("My name is: " + name + " and I am " + age + " years old ");//whatever you put in the bracket can be called in using . and the method name ex. speak
	}

	void sayHello() {
		System.out.println("Hello there!");
	}
	
public class App {

	public static void main(String[] args) {
		System.out.println("Hello");
		System.out.println("there");
		
		Person person1 = new Person(); //here is creation of an object(Person)
		person1.name = "Stef Blogs";
		person1.age = 28;
		person1.speak();
		person1.sayHello();
		
		Person person2 = new Person();//And another object
		person2.name = "Kyle Granes";
		person2.age = 32;
		//Basically you can store info and reference the object created
		System.out.println(person1.name);
	}

}
