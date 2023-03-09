```java
        int heat;

        Scanner inp = new Scanner(System.in);

        System.out.print("Hava Sıcaklığı Kaç Derece: ");
        heat = inp.nextInt();

        if (heat<5){
            System.out.println("Kayak yapabilirsiniz.");
        }
        else if (heat>25){
            System.out.println("Yüzmeye gidebilirsin.");
        }

        if (heat>=5 && heat<=15){
            System.out.println("Sinemaya gidebilirsin.");
        }
        if (heat>=15 && heat<=25){
            System.out.println("Pikniğe gidebilirsin");
        }
```