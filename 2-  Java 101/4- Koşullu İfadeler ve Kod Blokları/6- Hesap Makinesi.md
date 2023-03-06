# İF-ELSE Yapısı Kullanarak
```java
       int n1,n2, select;

        Scanner input = new Scanner(System.in);

        System.out.print("İlk Sayıyı Giriniz: ");
        n1 = input.nextInt();
        System.out.print("İkinci Sayıyı Giriniz: ");
        n2 = input.nextInt();

        System.out.println("1-Toplama\n2-Çıkartma\n3-Çarpma\n4-Bölme");
        System.out.print("Seçiminiz: ");
        select = input.nextInt();

        if (select == 1){
            System.out.print("Toplama: "+ (n1+n2));
        } else if (select == 2) {
            System.out.print("Çıkarma: "+ (n1-n2));
        } else if (select == 3) {
            System.out.print("Çarpma: "+ (n1*n2));
        } else if (select == 4) {
            if (n2!=0){
                System.out.print("Bölme: "+ (n1/n2));
            }else
                System.out.println("Bir sayı 0'a bölünemez!");
        }
        else
            System.out.println("Yanlış seçim yaptınız, tekrar deneyin.");

```
# Switch-Case Yapısı Kullanarak
```java
        int n1,n2, select;

        Scanner input = new Scanner(System.in);

        System.out.print("İlk Sayıyı Giriniz: ");
        n1 = input.nextInt();
        System.out.print("İkinci Sayıyı Giriniz: ");
        n2 = input.nextInt();

        System.out.println("1-Toplama\n2-Çıkartma\n3-Çarpma\n4-Bölme");
        System.out.print("Seçiminiz: ");
        select = input.nextInt();

        switch (select){
            case 1:
                System.out.print("Toplama: "+ (n1+n2));
                break;
            case 2:
                System.out.print("Çıkarma: "+ (n1-n2));
                break;
            case 3:
                System.out.print("Çarpma: "+ (n1*n2));
                break;
            case 4:
                if (n2!=0){
                    System.out.print("Bölme: "+ (n1/n2));
                }else
                    System.out.println("Bir sayı 0'a bölünemez!");
                break;
            default:
                System.out.println("Yanlış seçim yaptınız, tekrar deneyin.");

```