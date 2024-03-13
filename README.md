import java.util.Scanner;

public class App {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in); // *fas a locicitacao para a pessoa responder */

        String questao = "Trabalho para casa e necesario ?";

        System.out.println(questao);

        System.out.println("[A] Perca de tempo");
        System.out.println("[B] Utilizar o tempo livre para o aprendisado");
        System.out.println("[C] Em algumas casos serve");
        System.out.println("[D] Nenhuma das alternativas");

        System.out.println("Digite sua resposta: ");
        String resposta = scanner.nextLine(); // *funcao para travar e agrada a pessa responder */
    }
}
