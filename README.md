class EmployeeDetails {   
int year;  
String name, address;
}  
public String getName() 
{  
    return name;  
}  
public void setName(String name) 
{  
    this.name = name;  
} 
public int getyear() 
{  
    return year;  
}  
public void setyear(int year) 
{  
    this.year= year;  
}   
public String getAddress() 
{  
    return address;  
}  
public void setAddress(String address)
 {  
    this.address = address;  
}  
public class Employee{  
    public static void main(String args[]) {  
        EmployeeDetails emp = new EmployeeDetails();  
        emp.setName("Robert");  
        emp.setyear("1994");
        emp.setAddress("64C- WallsStreet"); 
        emp.setName("Sam");  
        emp.setyear("2000");
        emp.setAddress("68C- WallsStreet"); 
        emp.setName("John");  
        emp.setyear("1999");
        emp.setAddress("26C- WallsStreet"); 
        
        System.out.println(emp);  
}
}          




