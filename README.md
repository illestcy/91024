// 1,3,5,7,9,11,13,15,17,19,21

import javax.print.attribute.standard.NumberUpSupported;

import java.util.Arrays;



public class BinaryTree {
        public static void main(String[] args) {
            
            
            int[] arr = new int[]{21,23,51,27,9,18,25,58,69,98};
            int temp;
            for(int i=0;i<arr.length;i++)
            {
                for(int sort=i+1;sort<arr.length;sort++)
                {
                    if(arr[i]>arr[sort])
                    {
                        temp=arr[i];
                        arr[i]=arr[sort];
                        arr[sort]=temp;
                    }
                }
            }
            System.out.println("Ascending Sort : "+Arrays.toString(arr));


            

        //     for(int i = 0; 1 < arr.length; i++){
        //         System.out.println(arr[i] + "");
        //     }
        //     System.out.println("Index Number : " + binarySearch(arr, 15));

        //     System.out.println("Second Index Number : " + Arrays.binarySearch(arr, 9));
            

        // }
        // private static int binarySearch(int [] numbers, int numberToFind) {

        //     int low = 0;

        //     int high = numbers.length -1;

        //     while (low <= high) 
        //     {
        //         int middlePosition = (low + high) / 2;
        //         int middleNumber = numbers[middlePosition];
                
        //         if(numberToFind == middleNumber){
        //             return middlePosition;
        //         }
        //         if(numberToFind < middleNumber){
        //             high = middlePosition-1;
        //         } else {
        //             low = middlePosition+1;
        //         }
            }
            // return -1;
        }

        
     
// }
