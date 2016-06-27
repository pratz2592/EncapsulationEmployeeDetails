# EncapsulationEmployeeDetails

public class EmployeeDetails {
    private int EmpID;
    private String empName;
    private int empAge;

      public int getEmpID(){
        return EmpID;
    }

    public String getEmpName(){
        return empName;
    }

    public int getEmpAge(){
        return empAge;
    }

    public void setEmpAge(int newValue){
        empAge = newValue;
    }

    public void setEmpName(String newValue){
        empName = newValue;
    }

    public void setEmpID(int newValue){
        EmpID = newValue;
    }
}
class Encapsulation{
    public static void main(String args[]){
    	EmployeeDetails obj = new EmployeeDetails();
         obj.setEmpName("Pratik");
         obj.setEmpAge(24);
         obj.setEmpID(100454);
         System.out.println("Employee Name: " + obj.getEmpName());
         System.out.println("Employee EmpID: " + obj.getEmpID());
         System.out.println("Employee Age: " + obj.getEmpAge());
    } 
}

Output:
Employee Name: Pratik
Employee EmpID: 100454
Employee Age: 24
