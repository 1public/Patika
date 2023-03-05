```java
        int r;
        double pi = 2.14;

        Scanner inp = new Scanner(System.in);

        System.out.print("Dairenin yarı çapını giriniz: ");
        r = inp.nextInt();

        double alan = pi * r * r;
        double cevre = 2 * pi * r;

        System.out.println("Dairenin Alanı: "+ alan);
        System.out.println("Dairenin Çevre: "+ cevre);
```
# Ödev: Java ile yarı çapını kullanıcıdan aldığınız dairenin alanını ve çevresini hesaplayan programı yazın.

```java
        int r, a;
        double pi = 3.14, alan;
        Scanner input = new Scanner(System.in);

        System.out.print("Yarıçapı Giriniz: ");
        r = input.nextInt();

        System.out.print("Merkez Açıyı Giriniz: ");
        a = input.nextInt();

        alan = (pi*(r*r)*a)/360;

        System.out.println("Alan: "+ alan);
```