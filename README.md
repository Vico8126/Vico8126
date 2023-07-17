import java.util.Scanner;

public class Main {
  public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);
    System.out.println("¿Qué sabor de helado te gustaría pedir?");
    String sabor = scanner.nextLine();
    System.out.println("¿Cuántas bolas de helado te gustaría pedir?");
    int bolas = scanner.nextInt();
    System.out.println("¡Perfecto! Has pedido " + bolas + " bolas de helado de " + sabor);
  }
}
