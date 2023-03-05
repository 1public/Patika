```java
int matematik, fizik, kimya, turkce, tarih, muzik;

        Scanner inp = new Scanner(System.in);

        System.out.print("Matematik Notunuzu Giriniz: ");
        matematik = inp.nextInt();
        System.out.print("Fizik Notunuzu Giriniz: ");
        fizik = inp.nextInt();
        System.out.print("Kimya Notunuzu Giriniz: ");
        kimya = inp.nextInt();
        System.out.print("Türkçe Notunuzu Giriniz: ");
        turkce = inp.nextInt();
        System.out.print("Tarih Notunuzu Giriniz: ");
        tarih = inp.nextInt();
        System.out.print("Müzik Notunuzu Giriniz: ");
        muzik = inp.nextInt();

        int toplam = (matematik+fizik+kimya+turkce+tarih+muzik);
        double ortalamaSonuc = toplam/6.0;

        System.out.println("Ortalmanız: " + ortalamaSonuc);

        String kontrol;
        kontrol = (ortalamaSonuc > 60) ? "Sınıfı geçti" : "Sınıfta kaldı";

        System.out.println(kontrol);

```