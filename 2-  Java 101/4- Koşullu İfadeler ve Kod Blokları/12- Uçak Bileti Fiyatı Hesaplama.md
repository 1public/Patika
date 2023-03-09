```java 
        int mesafe, yas, yolculukTipi;
        double ucret = 0.10;
        double toplamFiyat = 0, indirimTutari = 0, indirimTutari2 = 0;
        boolean isError = false;
        Scanner input = new Scanner(System.in);

        System.out.print("Mesafeyi Giriniz(KM): ");
        mesafe = input.nextInt();
        System.out.print("Yaşınızı Giriniz: ");
        yas = input.nextInt();
        System.out.print("1- Tek Yön\n2- Gidiş-Dönüş\nYolculuk Tipini Belirtiniz:");
        yolculukTipi = input.nextInt();

        // Girdi kontrolleri yapılıyor ve fiyat hesaplanıyor
        if ((mesafe > 0) && (yas > 0 && yas < 200)) {
            if (yolculukTipi == 1) {
                toplamFiyat = mesafe * ucret;
            } else if (yolculukTipi == 2) {
                toplamFiyat = (mesafe * ucret) * 2;
            } else {
                isError = true;
            }
        } else {
            isError = true;
        }

        // İndirim oranları hesaplanıyor
        if (yas < 12) {
            toplamFiyat -= toplamFiyat * 0.50;
        } else if (yas >= 12 && yas <= 24) {
            toplamFiyat -= toplamFiyat * 0.10;
        } else if (yas>65) {
            toplamFiyat -= toplamFiyat * 0.40;
        }

        if (yolculukTipi == 2) {
            toplamFiyat -= toplamFiyat * 0.20;
        }


        // Kullanıcıya çıktır veriliyor
        if (isError) {
            System.out.println("Hatalı veri girdiniz!");
        }
        else{

            System.out.println("Uçak Biletinin Fiyatı: "+ toplamFiyat + " TL");
        }

```