import java.util.Arrays;

public class MainClass {
   public static void main(String args[]) throws Exception {
      int array[] = { 2, 5, -2, 6, -3, 8, 0, -7, -9, 4 };
      Arrays.sort(array);
      printArray("Sorted array", array);
      
   }
   private static void printArray(String message, int array[]) {
      
      for (int i = 0; i < array.length; i++) {
         if(i != 0){
            System.out.print(", ");
         }
         System.out.print(array[i]);                     
      }
      System.out.println();
   }
}
array = insertElement(array, 9);
      system.out.println("With 1 added", +array[]);
