# Ucgen-cevre-alan
www.patika.dev


import java.util.Scanner;

public class hipotenus {
    public static void main(String[] args) {
        double a,b,c,cevre,alan,kök,u;
        System.out.println("ucgenin birinci kenarini giriniz.");
        Scanner a2=new Scanner(System.in);
        a=a2.nextDouble();
        System.out.println("ucgenin ikinci kenarini giriniz");
        Scanner b2=new Scanner(System.in);
        b=b2.nextDouble();
        System.out.println("ucgenin ucuncu kenarini giriniz");
        Scanner c2=new Scanner(System.in);
        c=c2.nextDouble();

        u=(a+b+c)/2;
        kök=u*(u-a)*(u-b)*(u-c);
        cevre=2*u;
        alan=Math.sqrt(kök);
        System.out.println("Ucegnin alani:"+ alan);
        System.out.println("ucgenin cevrsi:"+cevre);
        

    }
}
