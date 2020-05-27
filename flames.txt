import java.lang.*;
import java.io.*;
public class Main
{
   static int i,j;
   static int n=4;
  static int k,l,m;
    public static void main(String[] args)
    {
       String name1="mahe";
       String name2="yash";
       String name4="mahe";
       String name3="";
        for(i=1;i<name1.length();i++)
        {
            for(j=1;j<name2.length();j++)
            {
                if(name1.charAt(i)==name2.charAt(j))
                {
                    name1=name1.replace(name1.charAt(i),' ');
                    name1=name1.replaceAll(" ","");
                }
            }
        }
        System.out.println("result 1 is:"+name1);
    for(i=1;i<name4.length();i++)
        {
            for(j=1;j<name2.length();j++)
            {
                if(name4.charAt(i)==name2.charAt(j))
                {
                    name2=name2.replace(name2.charAt(j),' ');
                     name2=name2.replaceAll(" ","");
                }
            }
        }
System.out.println("result 2 is:"+name2);
k=name1.length();
System.out.println("count is:"+k);
l=name2.length();
System.out.println("count is:"+l);
m=k+l;
System.out.println("total count is:"+m);
String str="FLAMES";
System.out.println("context is:"+str);
if(m==1)
{
    System.out.println("flames is:Freind");
}
else if(m==2)
{
    System.out.println("flames is:Lover");
}
else if(m==3)
{
 System.out.println("flames is:affection");
}
else if(m==4)
{
    System.out.println("flames is:marriage");
}
else if(m==5)
{
    System.out.println("flames is:enemy");
}
else if(m==6)
{
    System.out.println("flames is:sister");
}
else if(m==7)
{
     System.out.println("flames is:Friend");
}
else if(m==8)
{
    System.out.println("flames is:Lover");
}
else if(m==9)
{
 System.out.println("flames is:affection");
}
else if(m==10)
{
    System.out.println("flames is:marriage");
}
else if(m==11)
{
    System.out.println("flames is:enemy");
}
else if(m==12)
{
    System.out.println("flames is:sister");
}
else if(m==13)
{
     System.out.println("flames is:Friend");
}
else if(m==14)
{
    System.out.println("flames is:Lover");
}
else if(m==15)
{
 System.out.println("flames is:affection");
}
else if(m==16)
{
    System.out.println("flames is:marriage");
}
else if(m==17)
{
    System.out.println("flames is:enemy");
}
else if(m==18)
{
    System.out.println("flames is:sister");
}
}
}