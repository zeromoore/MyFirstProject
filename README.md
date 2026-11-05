# MyFirstProject
CISC190 Lab - Getting Started with GitHub

In this lab, you will write a small Java program that simulates generating a simple shopping receipt and saving it to a text file.
The program will ask the user for an item name, price, and quantity, then calculate the total and write all details to a file named receipt.txt.

You will complete the lab step by step.
Do not start a new project for each part — expand the same file as you go.


## Setup
Create a new project named LabFileWrite.

Copy the Starter Code below into your Main.java file.

Complete the TODOs in order (Part A → Part B → Part C).

## Starter Code
import java.io.FileWriter;
import java.io.IOException;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) throws IOException {
        Scanner sc = new Scanner(System.in);

        // TODO A1: Ask the user for item name, price, and quantity
        // Example:
        // Item: Milk
        // Price: 3.49
        // Quantity: 2

        // TODO B1: Calculate the total cost (price * quantity)

        // TODO C1: Create a FileWriter for "receipt.txt"
        // TODO C2: Write all purchase details to the file
        // TODO C3: Close the FileWriter and print "Receipt saved!"
    }
}

## Instructions
Part A — User Input 
A1 : Ask for item name using nextLine().
A2 : Ask for price (double) and quantity (int).
A3 : Store these values in variables.

Part B — Calculation 
B1 : Compute total = price × quantity.

Part C — Writing to a File
C1 : Create a FileWriter for receipt.txt.
C2 : Write the details to the file, one per line (Item, Price, Quantity, Total).
C3 : Close the file and print “Receipt saved!”.

## How to Run
1. Open the program in your IDE.
2. Enter item name and price, then the quantity number.
3. View the contents within the receipt and the total price.
   Edit added by Tatiana Ballesteros
   
## Example Output (Console)
Enter item name: Milk
Enter price: 3.49
Enter quantity: 2
Receipt saved!
## Content of receipt.txt
Item: Milk 
Price: $3.49
Quantity: 2
Total: $6.98
