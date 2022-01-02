
import java.util.Scanner;

public class Main{
    public static void main(String[] args) {


        int Math, Pyhsic, Turkish, Music, Chemistry, History;
        double average;
        String result;
        Scanner inp = new Scanner(System.in);

        System.out.println("Matematik Notunuzu Giriniz");
        int MathNote = inp.nextInt();

        System.out.println("Kimya Notunuzu Giriniz");
        int ChemistryNote = inp.nextInt();

        System.out.println("Turkce Notunuzu Giriniz");
        int TurkıshNote = inp.nextInt();

        System.out.println("Tarih Notunuzu Giriniz");
        int HistoryNote = inp.nextInt();

        System.out.println("Muzik Notunuzu Giriniz");
        int MusicNote = inp.nextInt();

        System.out.println("Fizik Notunu Giriniz");
        int PhysicNote = inp.nextInt();
        average = (MathNote+ChemistryNote+TurkıshNote+HistoryNote+MusicNote+PhysicNote) / 5.0;
        result = average > 60 ?"Sınıfı gectiniz":"Sınıfta kaldınız";
        System.out.println(average  + " "+ result);
    }
}
