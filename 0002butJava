package com.company;
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int []box = new int[10];
        Scanner x = new Scanner(System.in);
        System.out.print("Enter size of the array : ");
        int arr = x.nextInt();
        for (int i = 0; i<arr ; i=i+1){
            box[i] = x.nextInt();
        }
        int min = box[0];
        int max = box[0];
        for (int i = 1; i < arr ; i++){
            if(min>box[i]){
                min = box[i];
            }
            if(max<box[i]){
                max = box[i];
            }
        }
        System.out.println("minimum of array is : " + min);
        System.out.println("maximum of array is : " + max);
    }
}
