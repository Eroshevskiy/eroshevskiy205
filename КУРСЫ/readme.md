## https://live.skillbox.ru/playlists/code/yazyki-programmirovaniya/
## [Курс Ерошевский.docx](https://github.com/Eroshevskiy/eroshevskiy205/files/7940296/default.docx)

# Перешел на другой курс (https://live.skillbox.ru/playlists/code/java-razrabotka/)

## Пример №1
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
[image](https://user-images.githubusercontent.com/97594146/154117138-12bd9dd3-9a40-43bf-86ea-dd9f65b80144.png)

## Пример №2

<br/>Замечание i= i+1 тоже самое,что i++


<br/>public class Main {
    <br/>public static void main(String[]args){
       <br/> System.out.println("Кофе-машина");

        int moneyAmount = 12;

        int[] drinkPrice = {150, 80, 20};
        String[] drinkNames = {"Капучино", "Эспрессо", "Молоко"};

        boolean canBuyAnything = false;

        for (int i = 0; i <3; i = i +1) {
            if (moneyAmount>= drinkPrice[i]){
                System.out.println("Вы можете купить" + drinkNames[i] );
                canBuyAnything = true;
            }
        }

        if (canBuyAnything == false){
            System.out.println("Недостаточно средств");
        }
    }




