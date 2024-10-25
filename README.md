# ProjetoForDobro
Idem 25/10

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ProjetoForDobro
{
    public class Program
    {
        static void Main(string[] args)
        {
            /*Solicite e receba  um numero inteiro e exiba o dobro dos proximos
             * 10 numeros a partir do valor que se insere.
            */
            Console.WriteLine("Informe o numero: ");
            int numero = Convert.ToInt32(Console.ReadLine());

            for (int i = 1; i <= 10; i++)
            {
                numero *= 2;
                Console.WriteLine("Numero: " + numero);
            }
               Console.ReadKey();
        }
    }
}
