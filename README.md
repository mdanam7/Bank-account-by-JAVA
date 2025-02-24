# Bank-account-by-JAVA
By sharing this code I am starting my GITHUB journey....
<br>
AUTHOR - MD AHSUN BHUIYAN ANAM
public class BankAccount{
    public String name;
    public String id;
    public double balance;
    public void deposit(double amount)
    {
        balance+=amount;
    }
    public void withdraw(double amount)
    {
        balance -=amount;
    }
    public static void main(String args[])
    {
        BankAccount acc1= new BankAccount();
        acc1.name="RAFI";
        acc1.id="012";
        acc1.balance=200;
        acc1.deposit(10);
        acc1.withdraw(200);
        System.out.println("NAME:"+acc1.name);
        System.out.println("ID:"+acc1.id);
        System.out.println("BALANCE:"+acc1.balance);
    }
}