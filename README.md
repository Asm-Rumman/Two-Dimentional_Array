
package twodimensionalarry;

public class TwoDimensionalArry {

    public static void main(String[] args) {
     
        int[][] a={{35,25,17},{55,12,37}};
        int[][] b={{23,65,32},{44,12,88}};
        
        int rows=a.length;
        int cols=a[0].length;
        int[][] sum=new int[rows][cols];
        
        for(int r=0;r<rows;r++){
            for(int c=0;c<cols;c++){
                sum[r][c]=a[r][c]+b[r][c];
                
            }
        }
        
            System.out.println("Sum of those two Arrays are :");
            for(int r=0;r<rows;r++){
                for(int c=0;c<cols;c++){
                    System.out.print(sum[r][c]+"\t");
            
            }
                System.out.println();
        
    
    }
    }
    
}
