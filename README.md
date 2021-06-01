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


package firstproject;

public class StringExamples {
public static void main(String args[]) {
	//getchars by lieral
	String s="Welcome in India";
	char[] ch=new char[10];
	s.getChars(3,10,ch,0);
	System.out.println(ch);
//indexOf(int ch)
	String a="hello world";
	System.out.println("Index of w="+a.indexOf("w"));
	//indexOf(String substring, int fromIndex)
	String s1="NITIKA PATEL";
	int index=s1.indexOf("PATEL",5);
	System.out.println("indexOf String substring, int fromIndex:"+index);
// indexOf(int char, int fromIndex)
	String b="Nitika patel";
	int index1=b.indexOf("e",1);
	System.out.println(index1+" ");
//string intern
	String s3="NITIKA";
	String s5=s3.intern();
	String s4= new String("NITIKA");
	String s6=s4.intern();
	System.out.println(s5==s6);
	System.out.println(s3==s4);
	System.out.println(s3==s6);
	System.out.println(s6==s4);
//String isEmpty
	String c="";
	String d="NITIKA";
    if(c.length()==0 || c.isEmpty()) 
    	System.out.println("String is empty");
    else
    	System.out.println("String is not empty");
    
    if(d.length()==0 || d.isEmpty()) 
    
    	System.out.println("String is empty");
        else
        	System.out.println("String is not empty");
//String JOIN
    String date= String.join("/","31","05","2021");
    System.out.println(date);
    String time=String.join(":","05","10","10");
    System.out.println(time);
    //String lastIndexOf()
    String a1="this is index of example";
    int index2=a1.indexOf("x");
    System.out.println(index2);
//String lastIndexOf(int ch, int fromIndex)
    String a2="this is index of example";
    int index3=a2.indexOf("s",5);
    System.out.println(index3);
//String length
    String b1="NITIKA";
    System.out.println("length of string:"+b1.length());
    String c1="NITIKA PATEL";
    if(c1.length()>0)
    {
    	System.out.println("The length of the string:"+c1.length());
    }
//String replace
    String d1="Nitika patel";
    String r = d1.replace('a','e');
    System.out.println(r);
    
    String d2="Nitika Patel";
    String r1=d2.replace("patel","Nikku");
    System.out.println(r1);
    
}
}
