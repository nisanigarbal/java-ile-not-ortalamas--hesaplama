# java-ile-not-ortalamas--hesaplama
ders notlarının ortalamasını alma

import java.util.Scanner;
class main {
    public static void main ( String []args) {

        Scanner matematik = new Scanner(System.in);
        System.out.print("matematik notunu giriniz:");
        int a = matematik.nextInt();

        Scanner fizik = new Scanner(System.in);
        System.out.print("fizik  notunu giriniz:");
        int b = fizik.nextInt();

        Scanner kimya = new Scanner(System.in);
        System.out.print("kimya  notunu giriniz:");
        int c = kimya.nextInt();

        Scanner turkce = new Scanner(System.in);
        System.out.print("turkce notunu giriniz:");
        int d = turkce.nextInt();

        Scanner tarih = new Scanner(System.in);
        System.out.print("tarih notunu giriniz:");
        int e = tarih.nextInt();

        Scanner muzik = new Scanner(System.in);
        System.out.print("muzik notunu giriniz:");
        int f = muzik.nextInt();

        double ortalama = ((a+b+c+d+e+f)/6);
        System.out.print("ortalamanız:" + ortalama );

        String sonuc= ortalama >= 60 ? "sınıfı geçtiniz " : "sınıfta kaldı";
        System.out.println(sonuc);


    }
}
