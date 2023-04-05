# kitle
import java.util.Scanner;
Kilo (kg) / Boy(m) * Boy(m)

public class VucutKitleIndeks {
    public static void main(String[] args) {
        Scanner inp= new Scanner(System.in);
        double boy,kilo ,kitleEndeks;

        System.out.print("Lutfen boyunuzu giriniz (m) :");
        boy=inp.nextDouble();

        System.out.print("Lutfen kilonuzu giriniz (kg) :");
        kilo=inp.nextDouble();

         kitleEndeks = kilo / (boy * boy);

        System.out.println("Vücut kitle endeksiniz : "+kitleEndeks);
    }
}
