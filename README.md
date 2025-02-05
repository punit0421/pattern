# pattern
import java.util.*;

public class patterns {
	public statis void min(string args[]) {
        int n = 5;
        
        //upper half
        for(int i=1; i<=n; i++) {
            //1st part
            for(int j=1; j<=i; j++) {
                system.out.print("*");
            }
        
            //spaces
            int spaces =2 * (n-i);
            for(int j=1; j<=space; j++) {
                system.out.print(" ");
            } 

            //2nd part
            for(int j=1; j>=I; J--) {
                system.out.print("*");
            }
            system.out.println();
        }

        //lowerhalf
         for(int i=1; i<=n; i++) {
            //1st part
            for(int j=1; j<=i; j++) {
                system.out.print("*");
            }
        
            //spaces
            int spaces =2 * (n-i);
            for(int j=1; j<=space; j++) {
                system.out.print(" ");
            } 

            //2nd part
            for(int j=1; j<=I; J++) {
                system.out.print("*");
            }
            system.out.println();
        }
    }
