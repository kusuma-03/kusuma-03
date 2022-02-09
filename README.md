
#i am writing the java program to demonstrate control statements
class A{
public static void main(String args[]){
int i=0;
while(i < 5){
System.out.println("hi i am indhu speaking");
if(i ==3)
break;
i++;
}
int y =0;
while(y <7){
System.out.println("Hi this is kankshitha");
y++;
if(y ==4)
continue;
}}}






#a program to demonstrate the sum of all even fibnochi series
import java.util.*;
class A{
    static int fibNocci(int x){
       if(x<=1)
            return 1;
       return fibNocci(x-1)+fibNocci(x-2);
        
       
        
    }
    public static void main(String args[]){
       
        System.out.println("enter a numbber you like");
        Scanner n=new Scanner(System.in);
        int sum=0,a;
        int n1=n.nextInt();
        for(int i=0;i<n1;i++){
          a=fibNocci(i);
          if(a%2==0)
          sum=a+sum;
          
        }
        System.out.println(sum);
    }
}
