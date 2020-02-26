# Copy-Array-Java_interview_practice
Java program to copy one array into another
package copyarray;

/**
 *
 * @author Dinesh Nanda
 */

public class CopyArray {

    public static void main(String[] args) {
        
        int [] arr = {3, 1, 4, 2, 6};
        
        int [] new_arr;
        
        new_arr = new int[arr.length];
        
        System.out.println("Given Array: ");
        
        for(int i = 0; i < arr.length; i++){
            System.out.print(arr[i] + " ");
        }
        
        System.out.println();
        
        for(int i = 0; i < arr.length; i++){
            new_arr[i] = arr[i];
        }
        
        System.out.println("New Array: ");
        
        for(int i = 0; i < arr.length; i++){
            System.out.print(new_arr[i] + " ");
        }
    }
}
