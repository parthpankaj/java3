# java3
public class swap {
	public static void main(String[] args)
	{ 
		int a = 10; 
		int b = 20; 
		System.out.println("Before swap:");
		System.out.println("a value: "+a); 
		System.out.println("b value: "+b);
		a=a+b;
		b=a-b;
		a=a-b; 
		System.out.println("After swap:"); 
		System.out.println("a value: "+a); 
		System.out.println("b value: "+b);
		
	}
}



Before swap:
a value: 10
b value: 20
After swap:
a value: 20
b value: 10
