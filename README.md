
class Employee {
    String name;
    int age;
    String department;

    Employee(String name, int age, String department) {
        this.name = name;
        this.age = age;
        this.department = department;
    }

    void displayDetails() {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Department: " + department);
    }
}

public class Main {
    public static void main(String[] args) {
        Employee emp1 = new Employee("John Doe", 30, "HR");
        Employee emp2 = new Employee("Jane Doe", 25, "Marketing");

        System.out.println("Employee 1 Details:");
        emp1.displayDetails();

        System.out.println("\nEmployee 2 Details:");
        emp2.displayDetails();
    }
}


Output:


Employee 1 Details:
Name: John Doe
Age: 30
Department: HR

Employee 2 Details:
Name: Jane Doe
Age: 25
Department: Marketing
# Class-and-object-instance-
