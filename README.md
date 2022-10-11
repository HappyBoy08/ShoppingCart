# ShoppingCart
package ShoppingCard;
import java.util.Scanner;
public class Project1  {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
        int ch;
        Scanner sc= new Scanner(System.in);
        System.out.println("Enter your Name:");
		String name= sc.next();
        System.out.println("Enter your Email ID:");
		String EmailAddress=sc.next();
		String s1="Mobile";
		System.out.println("+1 '. Mobile'");
		String s2="Laptop";
		System.out.println("+2 '. Laptop'");
		String s3="Electronic Appliances";
		System.out.println("+3 '. Electronic Appliances'");
		String s4="Perfumes";
		System.out.println("+4 '. Perfumes'");
		System.out.println("Enter your choice:");
		ch=sc.nextInt();
		switch (ch)
		{
		case 1:
			String s6="Samsung";
			System.out.println("+1 '. Samsung'");
			String s7="Apple";
			System.out.println("+2 '. Apple'");
			String s8="Oneplus";
			System.out.println("+3 '.Oneplus'");
			String s9="Oppo";
			System.out.println("+4 '. Oppo'");
			String s10="Redmi";
			System.out.println("+5 '. Redmi'");
			System.out.println("Enter your choice:");
			ch=sc.nextInt();
			switch (ch)
			{
			case 1:
				System.out.println("Thank you for purchasing Samsung Phone. It will be delivered soon");
				break;
			case 2:
				System.out.println("Thank you for purchasing Apple Phone. It will be delivered soon");
				break;
			case 3:
				System.out.println("Thank you for purchasing Oneplus Phone. It will be delivered soon");
				break;
			case 4:
				System.out.println("Thank you for purchasing Oppo Phone. It will be delivered soon");
				break;
			case 5:
				System.out.println("Thank you for purchasing Redmi Phone. It will be delivered soon");
				break;
			}
			break;
		case 2:
			String s11="Dell Laptop";
			System.out.println("+1'. Dell'");
			String s12="Apple Macbook Air Laptop";
			System.out.println("+2'. Apple Macbook Air'");
			String s13="HP Laptop";
			System.out.println("+3'. HP'");
			String s14="Asus";
			System.out.println("+4'. Asus'");
			String s15="Lenovo";
			System.out.println("+5'. Lenovo'");
			System.out.println("Enter your Choice:");
			ch= sc.nextInt();
			switch (ch)
			{
			case 1:
				System.out.println("Thank you for purchasing Dell laptop. It will be delivered soon");
				break;
			case 2:
				System.out.println("Thank you for purchasing Apple Macbook Air Laptop. It will be delivered soon");
				break;
			case 3:
				System.out.println("Thank you for purchasing HP Laptop. It will be delivered soon");
				break;
			case 4:
				System.out.println("Thank you for purchasing Asus Laptop. It will be delivered soon");
				break;
			case 5:
				System.out.println("Thank you for purchasing Lenovo Laptop. It will be delivered soon");
				break;
			}
			break;
		case 3:
			String s16="Mixer";
			System.out.println("+1'. Mixer'");
			String s17="Bread Toaster";
			System.out.println("+2'. Bread Toaster'");
			String s18="Steam Iron";
			System.out.println("+3'. Steam Iron'");
			String s19="Microwave";
			System.out.println("+4'. Microwave'");
			String s20="Television";
			System.out.println("+5'. Television'");
			System.out.println("Enter your Choice:");
			ch=sc.nextInt();
			switch (ch)
			{
			case 1:
				System.out.println("Thank you for purchasing Mixer. It will be delivered soon");
				break;
			case 2:
				System.out.println("Thank you for purchasing Bread Toaster. It will be delivered soon");
				break;
			case 3:
				System.out.println("Thank you for purchasing Steam Iron. It will be delivered soon");
				break;
			case 4:
				System.out.println("Thank you for purchasing Microwave. It will be delivered soon");
				break;
			case 5:
				System.out.println("Thank you for purchasing Television. It will be delivered soon");
				break;
			}
			break;
		case 4:
			String s21="Fogg";
			System.out.println("+1'. Fogg'");
			String s22="Denver";
			System.out.println("+2'. Denver'");
			String s23="Signatures";
			System.out.println("+3'. Signatures'");
			String s24="Wild Stone";
			System.out.println("+4'. Wild Stone'");
			String s25="Engage";
			System.out.println("+5'. Engage'");
			System.out.println("Enter your Choice:");
			ch=sc.nextInt();
			switch (ch)
			{
			case 1:
				System.out.println("Thank you for purchasing Fogg. It will be delivered soon");
				break;
			case 2:
				System.out.println("Thank you for purchasing Denver. It will be delivered soon");
				break;
			case 3:
				System.out.println("Thank you for purchasing Signatures. It will be delivered soon");
				break;
			case 4:
				System.out.println("Thank you for purchasing Wild Stone. It will be delivered soon");
				break;
			case 5:
				System.out.println("Thank you for purchasing Engage. It will be delivered soon");
				break;
			}
			break;
			default:
				System.out.println("Sorry, The Product is not available. Thank you for visiting us...!! ");
					
		}
	}

}
// Output:
Enter your Name:
Sanjay
Enter your Email ID:
sanjay@gmail.com
+1 '. Mobile'
+2 '. Laptop'
+3 '. Electronic Appliances'
+4 '. Perfumes'
Enter your choice:
1
+1 '. Samsung'
+2 '. Apple'
+3 '.Oneplus'
+4 '. Oppo'
+5 '. Redmi'
Enter your choice:
2
Thank you for purchasing Apple Phone. It will be delivered soon
//
