using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Sum_Digits
{
    class Program
    {
        static void Main(string[] args)
        {
            int n = int.Parse(Console.ReadLine());

            int num = 0;

            while (n > 0)
            {
                num = num + (n % 10);
                n = n / 10;
            }
           
            Console.WriteLine(num);
        }
    }
}
