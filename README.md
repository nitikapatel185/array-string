# array-s

//String literals
package firstproject;

public class StringLiteral {
public static void main(String args[]) {
	String a="nitika";
	System.out.println(a);
	
	String b="nitika";
	System.out.println(b);
}
}

//String new keywords
package firstproject;

public class StringNew {
public static void main(String args[]) {
	String a = new String("nitika");
	System.out.println(a);
	
	String b = new String("patel");
	System.out.println(b);
}
}

//String by equal operator
package firstproject;

public class Segual {
public static void main(String srga[]) {
	String a="lion";
	System.out.println(a);
	String b=new String("LION");
	System.out.println(b);
	if(a.equals(b))
	{
		System.out.println("true");
	}
	else
	{
		System.out.println("False");
	}
}
}

//Syring Comaprison
package firstproject;

public class Scompare {
public static void main(String args[]) {
	String a="nitika";
	String b="patel";
	String c="patel";
	System.out.println(c.compareTo(b));
	System.out.println(a.compareTo(b));
	System.out.println(b.compareTo(a));
}
}
