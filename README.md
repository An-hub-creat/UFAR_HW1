# UFAR_HW1
using System;

namespace ConsoleApp3
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("What's the weather in Celsus? ");
            double weather = Convert.ToDouble(Console.ReadLine());
            if (weather >= 0 && weather <= 50)
            {
                Console.WriteLine("the weather is amazing! ");

            }
            else if (weather > 50)
            { 
                Console.WriteLine("it's abnormally hot! ");
            

            }
            else
            {
                Console.WriteLine("it's freezing! ");
            }

            Console.ReadKey();       
        }
    }
}

 
