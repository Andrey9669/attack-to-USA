# attack-to-USA
просто создал фейк аттакер на базы США я сделал неплохой функцыонал ну старался и советую новичкам посмотреть там для них будет новые вещи полезные
код ниже


 // так сегодня мы будем делать код для взлома пентагона а также взлом кодом для взлома спутников для информацыии.
 // (все это не по настоящиму это шуточная программа которая никого не взломает).

 import java.util.Scanner; // импортируем утилиту Scanner для получения данных от пользователя.

 public class Main {
     public static void main(String[] args) throws InterruptedException {
         Scanner scan = new Scanner(System.in);
         System.out.println("введите последовательность кода (используя 5 символов)"); // получаем данные от пользователя для дальнейших действий

         String nums = scan.nextLine();


         if (nums.length() != 5) {
             System.out.println("error");
             System.exit(0);
// условие что бы проверить пользователь ввел 5 символов или нет

     } else {
             if (nums.length() == 5) {
                 System.out.println("мы собираем информацыю \nподождите пожалуйста это может занять некоторое время");
                 Thread.sleep(10000);
                 for (int i = 0; i < 10000; i++) {
                     nums += 1;
                     nums += 0;
                     System.out.println(nums);
                 }
                 // есле вс енорм делаем собственно "атаку"
             }

             String target1 = ("\n\tUSA, pentagon, index - 10187272516\n");
             String target2 = ("\tUSA, White house, index - 817676812209");
             System.out.println("спасибо за ожидание, выберите цель атаки: " + target1 + target2 + "\n\t\t\tchoose  1st or 2nd\n\t\t\t click 1 or 2 ");
             Scanner scan2 = new Scanner(System.in);
             String choose = scan2.nextLine();
             if (choose == "1");
             {
                 System.out.println("Проводим DDos атаку... 0%");
                 Thread.sleep(200);
                 System.out.println("Проводим DDos атаку... 10%");
                 Thread.sleep(200);
                 System.out.println("Проводим DDos атаку... 20%");
                 Thread.sleep(200);
                 System.out.println("Проводим DDos атаку... 50%");
                 Thread.sleep(200);
                 System.out.println("Проводим DDos атаку... 80%");
                 Thread.sleep(200);
                 System.out.println("Проводим DDos атаку... 90%");
                 Thread.sleep(200);
                 System.out.println("Проводим DDos атаку... 99%");
                 Thread.sleep(200);
                 System.out.println("DDos атака завершенна на 100%");
                 Thread.sleep(200);
                 System.out.println("собираем утечки информацыии 0%");
                 Thread.sleep(200);
                 System.out.println("собираем утечки информацыии 10%");
                 Thread.sleep(200);
                 System.out.println("собираем утечки информацыии 30%");
                 Thread.sleep(200);
                 System.out.println("собираем утечки информацыии 50%");
                 Thread.sleep(200);
                 System.out.println("собираем утечки информацыии 80%");
                 Thread.sleep(200);
                 System.out.println("собираем утечки информацыии 90%");
                 Thread.sleep(200);
                 System.out.println("информацыя собранна на 100%");
                 Thread.sleep(200);
                 System.out.println("входим в системму 0%");
                 Thread.sleep(200);
                 System.out.println("входим в системму 10%");
                 Thread.sleep(200);
                 System.out.println("входим в системму 30%");
                 Thread.sleep(200);
                 System.out.println("входим в системму 40%");
                 System.out.println("входим в системму 60%");
                 System.out.println("входим в системму 70%");
                 System.out.println("входим в системму 80%");
                 System.out.println("входим в системму 90%");
                 System.out.println("мы вошли в систему на 100%");
                 System.out.println("все готово, данные пентагона: \npassword - brrrSHIBIDIdopYEAS181666\nemeil - SKIBIdiBADABum777@govoranGMAILLL.coma\nname - STALInpro777\nbio - 13.1945.03, anatoly stalin vladimirovich, +49 001 81 273 ");
                 Thread.sleep(1000);
                 System.exit(0);
             }

             if (choose == "2"); {
                 System.out.println("наш тупой мозг на такое не способен ;)");
                 Thread.sleep(1000);
                 System.exit(0);
                 // используем принт для вывода якобы атак и Thread.sleep то бы остонавливать время ненадолго
             }
         }
     }
 }



 /*

 ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣤⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⠞⢿⣧⠀⠀ ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣴⣶⣶⡀⠀⠀⢀⡴⠛⠁⠀⠘⣿⡄⠀ ⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣾⣿⣿⣿⣷⣤⡴⠋⠀⠀⠀⠀⠀⢿⣇⠀ ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠺⣿⣿⣿⣿⣿⣿⣿⡆⠀⠀⠀⠀⠀⢸⣿⠀ ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢻⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠈⣿⡀ ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⢏⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⣿⡇ ⠀⠀⠀⠀⠀⠀⠀⠀⢠⣾⣷⣾⣿⣿⣿⣿⣿⣿⡆⠀⠀⠀⠀⠀⢿⡇ ⠀⠀⠀⠀⠀⠀⠀⢀⡾⣿⣿⣿⣿⣿⣿⣿⣿⣿⠁⠀⠀⠀⠀⠀⢸⡇ ⠀⠀⠀⠀⠀⠀⢠⡞⠁⢹⣿⣿⣿⣿⣿⣿⣿⣿⡆⠀⠀⠀⠀⠀⢸⠀ ⠀⠀⠀⠀⠀⣠⠟⠀⠀⠈⣿⣿⣿⣿⣿⣿⣿⣿⣷⠀⠀⠀⠀⠀⢸⠀ ⠀⠀⠀⠀⣰⠏⠀⠀⠀⠀⢻⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⠀ ⠀⠀⠀⣴⠋⠀⠀⠀⠀⠀⠈⣿⣿⣿⣿⣿⣿⣿⣿⡆⠀⠀⠀⠀⠀⠀ ⠀⠀⣼⠃⠀⠀⠀⠀⠀⠀⠀⢻⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀ ⢀⣼⠃⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀ ⡾⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣷⠀⠀⠀⠀⠀⠀ ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀ ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣼⣿⣿⣿⣿⣿⣿⣿⣿⡄⠀⠀⠀⠀⠀ ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⡀⠀⠀⠀⠀ ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⡀⠀⠀⠀ ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⣄⠀ ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠿⠛⠃



  */
