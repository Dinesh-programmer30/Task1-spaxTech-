import java.util.Scanner;
class Currency{
  public static void main(String[] args){
    double inr,usd,eu,ruble;
    Scanner s=new Scanner(System.in);
    System.out.println("Currency Converter...");
    System.out.println("Enter the amount in INR:");
    inr=s.nextDouble();
    System.out.println("Enter the Choice:");
    int choice=s.nextInt();
    switch(choice){
        case 1:
            usd=inr/90.91;
            System.out.println("INR to USd:"+usd);
        break;
        case 2:
            eu=inr/102;
            System.out.println("INR to EU:"+eu);
        break;
        case 3:
            ruble=inr/1.1;
            System.out.println("INR to ruble:"+ruble);
        break;
        default:
            System.out.println("Invalid choice");
    }
  }  
}
