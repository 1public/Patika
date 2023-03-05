```java
try {
            double tutar, kdvOrani, kdvTutari, kdvliTutar;

            Scanner kdv = new Scanner(System.in);

            System.out.print("Tutarı Giriniz: ");
            tutar = kdv.nextDouble();

            kdvOrani = (tutar>0 && tutar<1000) ? 0.18 : 0.8;

            kdvTutari = tutar * kdvOrani;
            kdvliTutar = tutar + kdvTutari;

            System.out.println("KDV'siz Tutar: " + tutar);
            System.out.println("KDV Oranı: " + kdvOrani);
            System.out.println("KDV Tutarı: " + kdvTutari);
            System.out.println("KDV'li Tutar: " + kdvliTutar);
        }
        catch (Exception exception){
            System.out.println("Tekrar deneyin");
        }
```