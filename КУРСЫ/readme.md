## https://live.skillbox.ru/playlists/code/yazyki-programmirovaniya/
## [Курс Ерошевский.docx](https://github.com/Eroshevskiy/eroshevskiy205/files/7940296/default.docx)

# Перешел на другой курс (https://live.skillbox.ru/playlists/code/java-razrabotka/)
<br/>public class Main {
   <br/> public static void main(String[]args){
       <br/> System.out.println("Кофе-машина - Олег Ерошевский");

        int moneyAmount = 12;

        System.out.println("Вы внесли " + moneyAmount + "руб.");

        int cappucinoPrice = 150;
        int espressoPrice = 80;
        int milkPrice = 20;

        boolean canBuyAnything = false;

        if(moneyAmount>=cappucinoPrice){
            System.out.println("Вы можете купить капучино");
            canBuyAnything = true;
        }

        if(moneyAmount>=espressoPrice){
            System.out.println("Вы можете купить эспрессо");
            canBuyAnything = true;
        }

        if(moneyAmount>=milkPrice){
            System.out.println("Вы можете купить молоко");
            canBuyAnything = true;
        }

        if(canBuyAnything == false){
            System.out.println("Недостаточно средств:( Изучайте Java и зарабатывайте много:))");
        }
    }
}
