# Polymorphism
Simple example of Polymorphism/Overloading
class Student{
    String name;
    int age;
    int marks;
    String Grade;

    public void studentInfo(String name){
        System.out.println(name);
    }
	public int studentInfo(){
       return age;
    }
	
}
class Main{
    public static void main(String [] args){
        Student s1 = new Student();
        s1.name = "Tarun";
		s1.age =39;
		s1.studentInfo(s1.name);
		System.out.println(s1.studentInfo());
		
		
    }
}
