import java.util.Scanner;

public class Zodyak {

    public static void main(String[] args){

        double dogumYili;
        double zodya;

        Scanner input = new Scanner(System.in);
        System.out.println("Doğum yılınızı Giriniz");
        dogumYili = input.nextInt();

        zodya = dogumYili % 12;

        if (zodya == 0){
            System.out.println(" Çin Zodyağı Burcunuz = Maymun");
        } else if (zodya == 1) {
            System.out.println(" Çin Zodyağı Burcunuz = Horoz");
        }else if (zodya == 2) {
            System.out.println(" Çin Zodyağı Burcunuz = Köpek");
        }else if (zodya == 3) {
            System.out.println(" Çin Zodyağı Burcunuz = Domuz");
        }else if (zodya == 4) {
            System.out.println(" Çin Zodyağı Burcunuz = Fare");
        }else if (zodya == 5) {
            System.out.println(" Çin Zodyağı Burcunuz = Öküz");
        }else if (zodya == 6) {
            System.out.println(" Çin Zodyağı Burcunuz = Kaplan");
        }else if (zodya == 7) {
            System.out.println(" Çin Zodyağı Burcunuz = Tavşan");
        }else if (zodya == 8) {
            System.out.println(" Çin Zodyağı Burcunuz = Ejderha");
        }else if (zodya == 9) {
            System.out.println(" Çin Zodyağı Burcunuz = Yılan");
        }else if (zodya == 10) {
            System.out.println(" Çin Zodyağı Burcunuz = At");
        }else if (zodya == 11) {
            System.out.println(" Çin Zodyağı Burcunuz = Koyun");
        }else {
            System.out.println("Sonuç Bulunamadı.");
        }


    }


}
