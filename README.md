mport java.util.Scanner;
public class Questao_1 {
 public static void main(String[] args) {
 Scanner scanner = new Scanner(System.in);
 // Entrada das 8 notas
 System.out.print("Digite a nota do 1º mensal: ");
 double nota1 = scanner.nextDouble();
 System.out.print("Digite a nota do 2º mensal: ");
 double nota2 = scanner.nextDouble();
 System.out.print("Digite a nota do 3º mensal: ");
 double nota3 = scanner.nextDouble();
 System.out.print("Digite a nota do 4º mensal: ");
 double nota4 = scanner.nextDouble();
 System.out.print("Digite a nota do 5º mensal: ");
 double nota5 = scanner.nextDouble();
 System.out.print("Digite a nota do 6º mensal: ");
 double nota6 = scanner.nextDouble();
 System.out.print("Digite a nota do 7º mensal: ");
 double nota7 = scanner.nextDouble();
 System.out.print("Digite a nota do 8º mensal: ");
 double nota8 = scanner.nextDouble();
 // Cálculo das médias bimestrais do 1º semestre
 double bimestre1 = (nota1 + nota2) / 2;
 double bimestre2 = (nota3 + nota4) / 2;
 double semestre1 = (bimestre1 + bimestre2) / 2;
 // Cálculo das médias bimestrais do 2º semestre
 double bimestre3 = (nota5 + nota6) / 2;
 double bimestre4 = (nota7 + nota8) / 2;
 double semestre2 = (bimestre3 + bimestre4) / 2;
 double mediaFinal = (semestre1 + semestre2) / 2;
 // Saída dos resultados
 System.out.println("\nRESULTADO FINAL");
 System.out.println("----------------------");
 System.out.printf("1º Bimestre: %.1f\n", bimestre1);
 System.out.printf("2º Bimestre: %.1f\n", bimestre2);
 System.out.printf("1º Semestre: %.1f\n", semestre1);
 System.out.println("----------------------");
 System.out.printf("3º Bimestre: %.1f\n", bimestre3);
 System.out.printf("4º Bimestre: %.1f\n", bimestre4);
 System.out.printf("2º Semestre: %.1f\n", semestre2);
 System.out.println("----------------------");
 System.out.printf("Média Final: %.1f\n", mediaFinal);
 }
}
1) Simulando um sistema escolar, crie um algoritmo em J
2) 
