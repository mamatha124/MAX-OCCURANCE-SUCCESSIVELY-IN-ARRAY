# MAX-OCCURANCE-SUCCESSIVELY-IN-ARRAY
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        int m=1;
        Scanner sc=new Scanner(System.in);
        int l=sc.nextInt();
        int n[]=new int[l];
        for(int i=0;i<l;i++){
            int k=sc.nextInt();
            n[i]=k;
        }
        for (int i=0;i<l-1;i++){
            if(n[i]==n[i+1]){
                m=m+1;
            }
            else
            m=1;
        }
        System.out.println("Max occurance:"+m);
        
    }
}
