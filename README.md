# How-To-Anything
your mom pat pat
using System;

namespace ders1
{
    class Program
    {
        static void Main(string[] args)
        {

        baslangic:

            int a, b;
            Console.Write("A: ");
            a = Convert.ToInt32(Console.ReadLine() );
            Console.Write("b: ");
            b = Convert.ToInt32(Console.ReadLine());

            if ( a > b)
            {

                Console.WriteLine("A, B Den Büyük!");
                goto baslangic;

            }
            else
            {
                Console.WriteLine("a, B den Küçük!");
                goto baslangic;
            }



        }
    }
}
