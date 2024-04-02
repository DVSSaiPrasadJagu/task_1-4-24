# task_1-4-24
Q1: Some Of Digiits In Number

public class someOfDigiitsInnum {
    public static void main(String[] args) {
        int number = 23;
        int sum = 0;

        // Extract the digits and add them to sum
        sum += number % 10;  // Add the last digit (3)
        number /= 10;        // Remove the last digit
        sum += number % 10;  // Add the remaining digit (2)

        System.out.println("Sum of digits in 23: " + sum);
    }
}
Sum of digits in 23: 5
PS D:\Java> 

Q2:
public class operators {

    public static void main(String[] args) {
        int a=50;
        int b=10;

        System.out.println(a); 50
        //increment
        System.out.println(a++);// output 50
        System.out.println(a++);// output 51  
        System.out.println(++a);// output  53

        // decrement
        System.out.println(b);// output 10
        System.out.println(b--);// output 10
        System.out.println(b--);// output 9
        System.out.println(--b);// output 7

        //quotionent
        System.out.println(a/b);

        //modulus
        System.out.println(a%b);
        System.out.println(2.5f%2); 
        // when you use the modulus operator with the floating point number the resultant is the remainder after dividing the first offering by second offering 
        //in this case 2.5 F % 2 is 0.5 this is because two point F / 2 is 1.25 and the remainder when 2.5 / 2 is 0.5
    }
    
}


