Begin 
In this lab, we have a base class, “Doctor,” and a subclass, “Surgeon.”


Step 1: Create a Java project named “inheritanceDemo.”
Step 2: Create a class named Doctor, and add the code below.

Doctor.java class
public class Doctor {
   String DoctorName;
   String Department;
  public void Doctor_Details() {
       System.out.println("Doctor Details...");
   }
}


Step 3: Create a class named Surgeon, and add the code below.
Surgeon.java class
public class Surgeon extends Doctor {
   void Surgeon_Details() {
       System.out.println("Surgeon  Detail...");
       System.out.println(Department = "Cardio");
   }
}


Step 4: Create a class named Hospital. In this class, we will create a main() method.
 Hospital.java class
public class Hospital {
   public static void main(String args[]) {
       Surgeon s = new Surgeon();
       s.Doctor_Details();
       s.Surgeon_Details();
   }
}


The project hierarchy will look like this: 


Step 5: Run your Java Project.
Output on Console:
Doctor Details...
Surgeon Detail...
Cardio

Based on the above example, we can say that Surgeon IS-A Child. This means a child class has an IS-A relationship with the parent class. This inheritance is known as the IS-A relationship between the child and parent class. 


