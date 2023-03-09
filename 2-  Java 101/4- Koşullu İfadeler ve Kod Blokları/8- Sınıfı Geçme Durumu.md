```java
        while (true) {

            int mat, fizik, turkce, kimya, muzik;

            Scanner input = new Scanner(System.in);

            System.out.print("Matematik notunuz: ");
            mat = input.nextInt();
            System.out.print("Fizik notunuz: ");
            fizik = input.nextInt();
            System.out.print("Türkçe notunuz: ");
            turkce = input.nextInt();
            System.out.print("Kimya notunuz: ");
            kimya = input.nextInt();
            System.out.print("Müzik notunuz: ");
            muzik = input.nextInt();

            mat = (mat < 0 || mat > 100) ? 0 : mat;
            fizik = (fizik < 0 || fizik > 100) ? 0 : fizik;
            turkce = (turkce < 0 || turkce > 100) ? 0 : turkce;
            kimya = (kimya < 0 || kimya > 100) ? 0 : kimya;
            muzik = (muzik < 0 || muzik > 100) ? 0 : muzik;


            double avarage = (mat + fizik + turkce + kimya + muzik) / 5;

            if (avarage <= 55) {
                System.out.println("Sınıfta kaldınız");
            } else {
                System.out.println("Tebrikler, sınıfı geçtiniz !");
            }

            System.out.println("Ortalamanız: " + avarage);

        }
```