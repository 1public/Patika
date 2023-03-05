```java
        int kacKm;
        double  kmBasinaTutar = 2.20, toplamTutar;
        int minimumOdenecekTutar = 20;
        int acilisUcreti = 10;
        Scanner musteri = new Scanner(System.in);

        System.out.print("Mesafeyi Girini(KM): ");
        kacKm = musteri.nextInt();

        toplamTutar = (kacKm * kmBasinaTutar) + acilisUcreti;
        toplamTutar = (toplamTutar<minimumOdenecekTutar) ? minimumOdenecekTutar:toplamTutar;

        System.out.println("Ödenecek Tutar: "+ toplamTutar);
```