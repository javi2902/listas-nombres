# listas-nombres
import java.util.ArrayList;
import java.util.Scanner;

public class ListaNombres {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        ArrayList<String> nombres = new ArrayList<>();

        // Ingresar 3 nombres
        for (int i = 0; i < 3; i++) {
            System.out.print("Ingrese un nombre: ");
            nombres.add(sc.nextLine());
        }

        // Mostrar los nombres
        System.out.println("Nombres ingresados:");
        for (String nombre : nombres) {
            System.out.println(nombre);
        }
    }
}
