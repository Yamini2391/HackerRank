##### Day 2 - operators

##### working code

########### this is locked stub code #######
```
import java.io.*;
import java.math.*;
import java.security.*;
import java.text.*;
import java.util.*;
import java.util.concurrent.*;
import java.util.regex.*;

public class Solution {
```
####### this part is the required submission #####
```
// Complete the solve function below.
    static void solve(double meal_cost, int tip_percent, int tax_percent) {
        double total= meal_cost+(double)tip_percent*meal_cost/100+(double)tax_percent*meal_cost/100;
        System.out.println(Math.round(total));


    }
```
####### remaining locked code ######
```
private static final Scanner scanner = new Scanner(System.in);

    public static void main(String[] args) {
        double meal_cost = scanner.nextDouble();
        scanner.skip("(\r\n|[\n\r\u2028\u2029\u0085])?");

        int tip_percent = scanner.nextInt();
        scanner.skip("(\r\n|[\n\r\u2028\u2029\u0085])?");

        int tax_percent = scanner.nextInt();
        scanner.skip("(\r\n|[\n\r\u2028\u2029\u0085])?");

        solve(meal_cost, tip_percent, tax_percent);

        scanner.close();
    }
}
```
