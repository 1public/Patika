```java
        int mont, day;
        String burc = "";

        boolean isError = false;

        Scanner input = new Scanner(System.in);

        System.out.print("Doğduğunuz ayı giriniz:");
        mont = input.nextInt();
        System.out.print("Doğduğunuz günü giriniz:");
        day = input.nextInt();

        if (day > 0 && day < 31) {

            if (mont == 1) {
                if (day < 22) {
                    burc = "Oğlak";
                } else {
                    burc = "Kova";
                }
            } else if (mont == 2) {
                if (day < 20) {
                    burc = "Kova";
                } else {
                    burc = "Balık";
                }
            } else if (mont == 3) {
                if (day < 21) {
                    burc = "Balık";
                } else {
                    burc = "Koç";
                }
            } else if (mont == 4) {
                if (day < 21) {
                    burc = "Koç";
                } else {
                    burc = "Boğa";
                }
            } else if (mont == 5) {
                if (day < 22) {
                    burc = "Boğa";
                } else {
                    burc = "İkizler";
                }
            } else if (mont == 6) {
                if (day < 23) {
                    burc = "İkizler";
                } else {
                    burc = "Yengeç";
                }
            } else if (mont == 7) {
                if (day < 23) {
                    burc = "Yengeç";
                } else {
                    burc = "Aslan";
                }
            } else if (mont == 8) {
                if (day < 23) {
                    burc = "Aslan";
                } else {
                    burc = "Başak";
                }
            } else if (mont == 9) {
                if (day < 23) {
                    burc = "Başak";
                } else {
                    burc = "Terazi";
                }
            } else if (mont == 10) {
                if (day < 23) {
                    burc = "Terazi";
                } else {
                    burc = "Akrep";
                }
            } else if (mont == 11) {
                if (day < 22) {
                    burc = "Akrep";
                } else {
                    burc = "Yay";
                }
            } else if (mont == 12) {
                if (day < 22) {
                    burc = "Yay";
                } else {
                    burc = "Oğlak";
                }
            } else {
                isError = true;
            }
        } else {
            isError = true;
        }

        if (isError) {
            System.out.println("Hatalı giriş yaptınız, tekrar deneyiniz");
        } else {
            System.out.println("Burcunuz: " + burc);
        }
```