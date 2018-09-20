# Vending-machine
Vending machine
package Assignments;

import java.util.Scanner;

public class VendingMachineChange {
      public static void main(String[] args) {
			  
    		      Scanner scan = new Scanner(System.in);
    		      System.out.println("Please, select your item and enter the price of it");
    		      int price = scan.nextInt();
    		      System.out.println("Your chosen item's price is: " +price+" cents");
    		      System.out.println("Your paid bill is $1 dollar");
    		     
    		      int rest =100-price;
    		      int quarters =rest/25;
    		      rest=rest%25;
    		      int dimes=rest/10;
    		      rest =rest%10; 
    		      int nickels=rest/5;
    		      rest=rest%5;
    		      int penny=rest;
    		   
    		      System.out.println("Thank you for your purchase"); 
    		      System.out.println("Your change is :" + (100-price)+ " cents");
    		      System.out.println(quarters+" quarters");
    		      System.out.println(dimes +" dimes");
    		      System.out.println(nickels +" nickels");
    		      System.out.println(penny +" pennies");
    		       
    		      scan.close();
    		    	
    			    } 
    		   }

