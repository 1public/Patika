```java
        int kenar1, kenar2;
        double  hipotenus;

        Scanner ucgen = new Scanner(System.in);

        System.out.print("1. Kenarı Giriniz: ");
        kenar1 = ucgen.nextInt();
        System.out.print("2. Kenarı Giriniz: ");
        kenar2 = ucgen.nextInt();

        hipotenus = Math.sqrt((kenar1*kenar1) + (kenar2*kenar2));

        System.out.println("Üçgen'in Hipotenüsü: "+ hipotenus);
```