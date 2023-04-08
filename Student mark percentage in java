import java.util.Scanner;

class Student {
  private int rollno, marks1, marks2, marks3;

  public void get() {
    Scanner sc = new Scanner(System.in);
    System.out.print("Enter Roll Number: ");
    rollno = sc.nextInt();
    System.out.print("Enter Marks in Subject 1: ");
    marks1 = sc.nextInt();
    System.out.print("Enter Marks in Subject 2: ");
    marks2 = sc.nextInt();
    System.out.print("Enter Marks in Subject 3: ");
    marks3 = sc.nextInt();
  }

  public float percentage() {
    float total = marks1 + marks2 + marks3;
    return (total / 3);
  }

  public void put() {
    System.out.println("Roll Number: " + rollno);
    System.out.println("Percentage: " + percentage() + "%");
  }
}

public class Main {
  public static void main(String[] args) {
    Student s = new Student();
    s.get();
    s.put();
  }
}
