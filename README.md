using System;
using System.Globalization;

class Program
{
    static void Main()
    {
        // Solicita ao usuário que digite o valor do raio
        Console.Write("Digite o valor do raio: ");
        // Lê o valor do raio como ponto flutuante
        double raio = double.Parse(Console.ReadLine(), CultureInfo.InvariantCulture);
        // Define o valor de PI
        double pi = 3.14159;
        // Calcula a área
        double area = pi * Math.Pow(raio, 2);
        // Exibe o resultado com 4 casas decimais
        Console.WriteLine("A=" + area.ToString("F4", CultureInfo.InvariantCulture));
    }
}
