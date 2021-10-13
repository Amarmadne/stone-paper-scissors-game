# stone-paper-scissors-game
//package com.code;

import java.util.Scanner;
import java.util.Random;

public class game {

    public static void main(String[] args) {
        // write your code here

       int n;
       do{
        Scanner sc = new Scanner(System.in);
        Random R = new Random();        System.out.println("welcome to the game\tstone\tpaper\tscissor\n\n enter 0 for stone \n enter 1 for paper \n enter 2 for scissor");
        int a = sc.nextInt();
        int b = R.nextInt(2);


          if(a==0){
            System.out.println("your choice = stone");
            }
           else if(a==1){
            System.out.println("your choice = paper");
            }
          else if(a==2){
            System.out.println("your choice = scissor");
            }
             
               
            if(a==1||a==2||a==0){
            if(b==0){
            System.out.println("cpmputer's choice = stone");
            }
           else if(b==1){
            System.out.println("computer's choice = paper");
            }
          else{
            System.out.println("computer's choice = scissor");
            }
}


            if (a == 0) {
                if (b == 2) {
                    System.out.println("congrats you won the game!");

                } else if (b == 1) {
                    System.out.println(" Bad luck computer won!");

                } else if(b==0) {
                    System.out.println("Its a Tie try again");
               }
               else{
               System.out.println("wrong choice");
               }
            } else if (a == 1) {
                if (b == 0) {
                    System.out.println("congrats you won the game!");

                } else if (b == 2) {
                    System.out.println(" Bad luck computer won!");

                } else if(b==1) {
                    System.out.println("Its a Tie try again");

                }
                else{
               System.out.println("wrong choice");
               }
            } else if (a == 2) {
                if (b == 1) {
                    System.out.println("congrats you won the game!");

                } else if (b == 0) {
                    System.out.println(" Bad luck computer won!");

                } else if(b==2){
                    System.out.println("Its a Tie try again");

                }
                else{
               System.out.println("wrong choice");
               }
               
            }
               else{
               System.out.println("wrong choice");
               }
            System.out.println("To play again press 1");
            n=sc.nextInt();
        }while(n==1);
    }

    }

