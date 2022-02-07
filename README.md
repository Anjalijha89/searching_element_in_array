# searching_element_in_an_array
package com.company;
import java.util.Scanner;
public class searching_in_array {
    public static void main(String args[]){
        int A[]={23,56,78,98,86,64,43,31};
        int key;
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter a key");
        key=sc.nextInt();
        for(int i=0;i<A.length;i++){
            if(key==A[i]){
                System.out.println("Element found at index:"+i);
                System.exit(0);
            }
        }
        System.out.println("Element not found");
    }
}
