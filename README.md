# Reversing-elements-

Reversing elements 

import java.util.*;

// Problem: Reversing string array

class Array{

    static void Reverse(int[] arr){

        int i=0; int j=arr.length-1;

        while (i<j) {

            int t = arr[i];

            arr[i] = arr[j];

            arr[j] = t;

            i++;

            j--;

        }

    }

    public static void main(String... args){

        int arr[]={1,2,3,4};

        for(int i=0;i<arr.length;i++) {

            System.out.println(arr[i]);

        }

        Reverse(arr);

        System.out.println();

        for(int i=0;i<arr.length;i++){

            System.out.println(arr[i]);

        }

    }

}

/*

1

2

3

4

4

3

2

1

 */

class Strrev{

    public static void main(String ... strrev){

        String str="welcome";

        String rstr=" ";

        char ch;

        System.out.println("Original string is : " + str);

        for(int i=0;i<str.length();i++){

            ch= str.charAt(i);

            rstr=ch+rstr;

        }

        System.out.println(" Reversed string is : "+ rstr);

    }

}

/*

Original string is : welcome

Reversed string is : emoclew 

 *
