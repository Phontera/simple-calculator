using System;

namespace Csharp
{
    class Program
    {
        static void Main(string[] args)
        {   int firstNumber = 0; 
            int secondNumber = 0;
            String symbol = "";
            int result = 0; 
            
            Console.WriteLine("Hello, I am a digital calculator. Welcome");

            Console.Write("Please enter First Number: "); 
            firstNumber = int.Parse(Console.ReadLine()); 

            Console.Write("Please enter desired symbol: "); 
            symbol = Console.ReadLine();

            Console.Write("Please enter Second Number: ");
            secondNumber = int.Parse(Console.ReadLine()); 

            if(symbol == "+")
            {
                result = firstNumber + secondNumber; 
            }

            else if (symbol == "-")
            {
                result = firstNumber - secondNumber;
            }

            else if (symbol == "/")
            {
                result = firstNumber / secondNumber; 
            }

            else if (symbol == "*")
            {
                result = firstNumber * secondNumber;
            }

            Console.WriteLine("Your answer is: " + result); 


        }   


    }
}
