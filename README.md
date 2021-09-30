# Addind-multiplying-using-methods-and-classes-without-constructer

import java.util.Scanner;
class Addone {
    int num1;
    int num2;

    void mergdata() {
        int result;
        result=num1+num2;
        System.out.println(" the sum of two numbers are  "+result);
    }
    void mult()
    {
        int result;
        result=num1*num2;
        System.out.println("the multiply of two numbers are  "+result);
    }
    void check()
    {
        if (num1>num2)
        {
            System.out.println("number one is grater than num two");
        }
        else
        {
            System.out.println("number two is grater than one");
        }
    }
    void onemore()
    {
        for(int i=num1;i<num2;i++)
        {
            System.out.print(" @");
    }
}
}
public class Add {
    public static void main(String args[]) {
        Addone numone = new Addone();
        Scanner obj = new Scanner(System.in);
        System.out.println("Enter the numbers you want to sum on");
        numone.num1 = obj.nextInt();
        numone.num2 = obj.nextInt();
        numone.mergdata();
        Addone numtwo = new Addone();
        numtwo.num1 = obj.nextInt();
        numtwo.num2 = obj.nextInt();
        numtwo.mult();
        Addone numthree=new Addone();
        numthree.num1 = obj.nextInt();
        numthree.num2 = obj.nextInt();
        numthree.check();
        Addone numfour=new Addone();
        numfour.num1 = obj.nextInt();
        numfour.num2 = obj.nextInt();
        numfour.onemore();
    }
}

