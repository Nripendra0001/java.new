import java.util.Scanner;

public class newSwitch {
   public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    int choice;
    do{
    System.out.println("1-For Addition of two numbers");
    System.out.println("2-For Substraction of two numbers");
    System.out.println("3-For Multiplication of two numbers");
    System.out.println("4-For Division of two numbers");
    System.out.println("5-Even or Odd check in two numbers");
    System.out.println("7-Exit");
    System.out.print("Enter your choice :");
     choice = sc.nextInt();
    switch(choice){
        case 1:
        System.out.print("Enter the first number :");
        int num = sc.nextInt();
        System.out.print("Enter the second number :");
        int num2 = sc.nextInt();
        int sum = (num+num2);
        System.out.println(sum);
        break;
        case 2:
        System.out.print("Enter the first number :");
        int num3 = sc.nextInt();
        System.out.print("Enter the second number :");
        int num4 = sc.nextInt();
        int subs = (num3-num4);
        System.out.println(subs);
        break;
        case 3:
         System.out.print("Enter the first number :");
        int num5 = sc.nextInt();
        System.out.print("Enter the second number :");
        int num6 = sc.nextInt();
        int mul = (num5*num6);
        System.out.println(mul);
        break;
        case 4:
         System.out.print("Enter the first number :");
        int num7 = sc.nextInt();
        System.out.print("Enter the second number :");
        int num8 = sc.nextInt();
        int div = (num7/num8);
        System.out.println(div);
        break;
        case 5:
         System.out.print("Enter the first number :");
        int x = sc.nextInt();
        if(x%2==0){
            System.out.println("Number is even");
        }
        else{
            System.out.println("Given number is odd");
        }
        break;
        case 7:
        System.out.println("Exit the program");
        break;
        default:
        System.out.println("Please enter the valid choice");
    }
       }
       while(choice!=7);{

       }
       
        



    

    
    
    

}
}
