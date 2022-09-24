# ***🌟Give Star If you find this helpful :)🌟***
# 1. ***Half Diamond Pattern***
### Code:Half Diamond Pattern
import java.util.Scanner;
public class Solution {
    
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        int n = s.nextInt();
        int i = 1;
        System.out.println("*");
        while (i <= n) {
            System.out.print("*");
            int j = 1;
            while (j <= i) {
                System.out.print(j);
                j++;
            }
            int k = i - 1;
            while (k > 0) {
                System.out.print(k);
                k--;
            }
            i++;
            System.out.println("*");
        }
        i -= 2;
        while (i > 0) {
            System.out.print("*");
            int j = 1;
            while (j <= i) {
                System.out.print(j);
                j++;
            }
            int k = i - 1;
            while (k > 0) {
                System.out.print(k);
                k--;
            }
            i--;
            System.out.println("*");
        }
        System.out.print("*");
    }
}

# 2. ***Parallelogram Pattern***
### Code:Parallelogram Pattern
import java.util.Scanner;
public class Main {
	
	public static void main(String[] args) {
		  Scanner scan = new Scanner(System.in);
        int n = scan.nextInt();
        int i = 1;
        while (i <= n) {
            int s = 1;
            while (s <= i-1) {
                System.out.print(" ");
                s++;
            }
           int j = 1;
            while (j <= n) {
                System.out.print("*");
                j++;
            }
            System.out.println();
            i++;
        }
	}
}

# 3. ***Sum Pattern***
### Code:Sum Pattern
import java.util.Scanner;
public class Main {
	
	public static void main(String[] args) {
			
       Scanner s=new Scanner(System.in);

int n=s.nextInt();

int i=1;

int sum=i;    

  while(i<=n){

int t=1;    //starting number    

  int j=1;

while(j<=i){                    

         if(t<i){

System.out.print(t+"+");            

   t++;                                          

   j++;

 }              

else{            

       System.out.print(t+"="+sum);            

        j++;

                      }

          }        

   System.out.println();    

      i++;      

     sum=sum+i;

        }
	}
}

# 4. ***Odd Square***
### Code:Odd Square
import java.util.Scanner;
public class Main {
	
	public static void main(String[] args) {
		 Scanner sc = new Scanner(System.in);
    int N = sc.nextInt();
    int i = 1,j;
    while(i<=N){
        int odd = 2*i-1;
        j=N;
        while(j>=i){
            System.out.print(odd);
            odd = odd +2;
            j--;
        }
        j = 1;
        int  p =1;
        while(j<=i-1){
            
            System.out.print(p);
            p= p+2;
            j++;
        }
        System.out.println();
        i++;
    }
	}
}


# ***🌟Give Star If you find this helpful :)🌟***
