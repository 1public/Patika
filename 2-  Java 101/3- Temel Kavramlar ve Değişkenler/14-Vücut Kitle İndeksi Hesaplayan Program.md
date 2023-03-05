```java
        double boy, kilo, kitleIndeksi;

        Scanner input = new Scanner(System.in);

        System.out.print("Kilonuzu Giriniz: ");
        kilo = input.nextDouble();
        System.out.print("Boyunuzu Giriniz: ");
        boy = input.nextDouble();

        kitleIndeksi = kilo / (boy*boy);

        System.out.println("Vicut Kitle İndeksiniz: " + kitleIndeksi);
```