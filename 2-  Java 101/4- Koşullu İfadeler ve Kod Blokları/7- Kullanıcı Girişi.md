```java
        while (true) {

            String userName, password, reset, newPassword, ePassword;

            Scanner inp = new Scanner(System.in);

            System.out.print("Kullanıcı Adınız: ");
            userName = inp.nextLine();
            System.out.print("Parolanız: ");
            password = inp.nextLine();

            if (userName.equals("patika") && password.equals("java123")) {
                System.out.println("Giriş Yaptınız !");
            } else {
                System.out.println("Bilgileriniz Yanlış !");

                ePassword = password;
                System.out.print("Parolanızı sıfırlamak için 1 tuşuna, tekar denemek için başka bir tuşa basınız: ");
                reset = inp.nextLine();

                while (true) {
                    if (reset.equals("1")) {
                        System.out.println("Yeni parola, hatalı girdiğiniz veya unuttuğunuz parola ile aynı olmamalı");
                        System.out.print("Yeni parolayı giriniz: ");
                        newPassword = inp.nextLine();

                        if (!newPassword.equals(ePassword) && !newPassword.equals("java123")) {
                            System.out.println("Yeni parola oluşturuldu");
                            break;
                        }
                    }

                }

            }


        }
```