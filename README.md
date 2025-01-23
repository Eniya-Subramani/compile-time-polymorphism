# compile-time-polymorphism
package complietimepolymorphism;
public class Complietimepolymorphism {

    //method to add two integers
    public int addition(int x,int y){
        return x+y;
    }
    //method to add three integers
    public int addition(int x,int y,int z){
        return x+y+z;
    }
    //method to add two doubles
    public double addition(double x,double y){
    return x+y;
}
    public static void main(String[] args) {
        //creating an object of the main method
       Complietimepolymorphism number = new Complietimepolymorphism ();
       //calling the overloaded methods
      
        int res1=number.addition(444, 555);
        System.out.println("addition of two integers:" +res1);
         int res2=number.addition(333,444,555);
        System.out.println("addition of two integers:" +res2);
        double res3=number.addition(10.15,20.22);
        System.out.println("addition of two doubles:" +res3);
    }
    
}
output:
addition of two integers:999
addition of two integers:1332
addition of two doubles:30.369999999999997
