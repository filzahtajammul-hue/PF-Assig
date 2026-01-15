# PF-Assig
Qno. 5


// Online Java Compiler
// Use this editor to write, compile and run your Java code online

  import java.util.Scanner;

public class PowerCalculation {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        // Fixed values
        double voltage = 220;
        double current = 5;

        double power = voltage * current;

        System.out.println("Voltage = " + voltage);
        System.out.println("Current = " + current);
        System.out.println("Power (Watts) = " + power);

        sc.close();
    }
}
