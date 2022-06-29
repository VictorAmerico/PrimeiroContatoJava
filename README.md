# Primeiro Contato Java
Meu primeiro exercício em Java

~~~~java
import java.util.Locale;

public class App {
    public static void main(String[] args) throws Exception {
        String nome = "Victor";
        int idade = 19;
        int peso = 80;
        double x = 10.256765;
        System.out.println("Meu nome é " + nome + ", tenho " + idade + " e peso " + peso );

        System.out.printf("%.2f%n", x);
        System.out.printf("%.4f%n",x);
        Locale.setDefault(Locale.ENGLISH);
        System.out.printf("%.4f%n",x);

        /* %f = ponto flutuante
         * %d = inteiro
         * %s = texto
         * %n = quebra de linha
         */

        System.out.printf("Meu nome é %s, tenho %d e peso %d. Além disso, %.2f %n ", nome, idade, peso, x);


        System.out.println("=====================================================");
        System.out.println("                 Exercício de fixação");     
        System.out.println("=====================================================");


        String product1 = "Computer";
        String product2 = "Office desk";

        int age = 30;
        int code = 5290;
        char gender = 'F';

        double price1 = 2100.0;
        double price2 = 650.50;
        double measure = 53.234567;

        System.out.println("Products:");
        System.out.printf("%s, wich price is $ %f %n", product1, price1);
        System.out.printf("%s, which price is $ %f %n", product2, price2);
        System.out.printf("Record: %d years old, code %d and gender: %s %n", age, code, gender);
        System.out.printf("Measue with eight decima places: %.8f %n", measure);
        System.out.printf("Rouded (Three decimal places): %.3f %n", measure);
        Locale.setDefault(Locale.ENGLISH);
        System.out.printf("Us decimal point: %.3f", measure);
    }
}


~~~~
