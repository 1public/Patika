```java
        double armut=2.14, elma=3.67, domates=1.11, muz =0.95, patlican=5.00, total = 0, kg;

        Scanner inp = new Scanner(System.in);
        System.out.print("Kaç Kilo Armut ? : ");
        kg = inp.nextDouble();
        total += kg * armut;
        System.out.print("Kaç Kilo Elma ? : ");
        kg = inp.nextDouble();
        total += kg * elma;
        System.out.print("Kaç Kilo Domates ? : ");
        kg = inp.nextDouble();
        total += kg * domates;
        System.out.print("Kaç Kilo Muz ? : ");
        kg = inp.nextDouble();
        total += kg * muz;
        System.out.print("Kaç Kilo Patlıcan ? : ");
        kg = inp.nextDouble();
        total += kg * patlican;

        System.out.println("Toplam Tutar: "+ total);
```