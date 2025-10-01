# Tarea
import java.util.Scanner;

public class fahrenheit {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);// Scanner para leer la entrada del usuario
        // Solicita la temperatura en grados Fahrenheit
        System.out.println("ingresa la temperatura en grados Fahrenheit:");
        // Lee la temperatura ingresada por el usuario
        double fahrenheit = sc .nextDouble();
        // Convierte la temperatura a grados Celsius
        double celsius = (fahrenheit - 32) * 5 / 9;
        // Muestra la temperatura en grados Celsius
        System.out.println("la temperatura en grados celsius es: " + celsius);
    }
}
