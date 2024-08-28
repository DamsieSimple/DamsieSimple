import java.util.Scanner;

public class IntNum
{
  /* public static void OddEven(int no) 
   {
      if ((no%2)==0)      
         System.out.println("EVEN");      
       else      
         System.out.println("ODD");     
      
   } */
      public static boolean isEven(int no)
   {
      if ((no%2)==0)
      return true;
      
      else
      return false;
      
   }
   
   public static void display(int no)
   {
      if (isEven(no))
      System.out.println("The Value is EVEN!");    
      else 
      System.out.println("The Value is ODD!");
   }
   
      public static void main (String[] args) 
   {
      Scanner scan = new Scanner(System.in);
      System.out.println("Input an Integer Number:");
      int num = scan.nextInt();
      
      display(num);
      
      //OddEven(num);
   }
}
