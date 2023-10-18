using System.ComponentModel.Design;
using System.Diagnostics.Tracing;
using System.Security.Cryptography.X509Certificates;

namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {
              
                string nome = "";
                 Console.WriteLine("Escreva seu nome:");
                 nome = Console.ReadLine();
                 Console.WriteLine("Seu nome é:");
                 Console.WriteLine(nome);

            
            Console.WriteLine("Escreva sua idade ");
            int id = int.Parse( Console.ReadLine());
            Console.WriteLine(id);

            if (id > 18)
            {
                Console.WriteLine("Pode tirar a carteira de motorista"); 


                Console.WriteLine();
            }
            else {
                Console.WriteLine("Não pode tirar a carteira de motorista");
                    }
      
        
        
        
        
        
        
        
        }   





    }
}



