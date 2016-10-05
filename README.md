# Test
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using static System.Console;

namespace Cee_Lo_v2
{
    class Program
    {
        static void Main(string[] args)
        {
            string Top = "Cee-Lo";
            Console.Title = Top;
            string userRes, userAns;
            Console.ForegroundColor = ConsoleColor.Red;
            WriteLine("Welcome to Cee-Lo do you want to play or look at the rules? (rules or play)");
            Console.ForegroundColor = ConsoleColor.Gray;
            string ready = ReadLine();
            string uReady = ready.ToUpper();
            if (uReady.Equals("RULES"))
            {
            
            }
        }
    }
}
