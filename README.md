using System;

class Program
{
    static void Main()
    {
        // Lendo os dois valores inteiros
        Console.Write("Digite o primeiro valor: ");
        int valor1 = int.Parse(Console.ReadLine());

        Console.Write("Digite o segundo valor: ");
        int valor2 = int.Parse(Console.ReadLine());

        // Calculando o produto
        int PROD = valor1 * valor2;

        // Exibindo o resultado
        Console.WriteLine($"PROD = {PROD}");
    }
}
