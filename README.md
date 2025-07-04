# Assignment-
Assignment 
#include <iostream>
using namespace std;

int main() {
    int arr[10]; // Declare a static array of size 10

    // Populate array with user input
    cout << "Enter 10 integers:" << endl;
    for(int i = 0; i < 10; i++) {
        cin >> arr[i];
    }

    // Print all values
    cout << "The values in the array are: ";
    for(int i = 0; i < 10; i++) {
        cout << arr[i] << " ";
    }
    cout << endl;

    return 0;
}
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int[] arr = new int[10]; // Declare a static array of size 10
        Scanner scanner = new Scanner(System.in);

        // Populate array with user input
        System.out.println("Enter 10 integers:");
        for (int i = 0; i < 10; i++) {
            arr[i] = scanner.nextInt();
        }

        // Print all values
        System.out.print("The values in the array are: ");
        for (int i = 0; i < 10; i++) {
            System.out.print(arr[i] + " ");
        }
        System.out.println();
    }
}
