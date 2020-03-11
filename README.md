# Laba
TTIT
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Ход_слона
{
    class Program
    {
        static void Main(string[] args)
        {
            int x1, y1, x2, y2;
            Console.WriteLine("Введите координаты первой клетки");
            Console.Write("Введите номер столбца: ");
            x1 = Convert.ToInt32(Console.ReadLine());
            Console.Write("Введите номер строки: ");
            y1 = Convert.ToInt32(Console.ReadLine());
            Console.Write("Введите номер столбца: ");
            x2 = Convert.ToInt32(Console.ReadLine());
            Console.Write("Введите номер строки: ");
            y2 = Convert.ToInt32(Console.ReadLine());

            if (Math.Abs(x1 - x2) == Math.Abs(y1 - y2) )
            {
                Console.WriteLine("Yes");
            }
            else
                Console.WriteLine("No");
            Console.ReadLine();
        }
    }
}
