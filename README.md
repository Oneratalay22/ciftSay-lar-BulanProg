import java.util.Scanner;
public class Main {
    public static void main(String[] args) {

        int k;
        Scanner inp = new Scanner(System.in);
        System.out.print("Lütfen bir sayı giriniz:");
        k=inp.nextInt();

        int i=0;
        while(i<=k){
            if (i%2==0){
                System.out.println(i);
            }
            i++;
        }
    }
}
