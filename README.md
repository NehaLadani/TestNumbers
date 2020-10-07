using System;

namespace FiveNumberTriangle
{
    class Triangle

    {
        static void Main(string[] args)
        {
            //int N;
            Console.Write($"Enter the value of N: ");
            int N = int.Parse(Console.ReadLine());

            for (int line = 1; line <= N; line++)
            {
                PrintLine(1, line);
            }
            for (int line = N - 1; line >= 1; line--)
            {
                PrintLine(1, line);
            }
        }
         static void PrintLine(int start, int end)
        {
            for (int i = start; i<=end; i++)
            {
                Console.WriteLine(i + " ");

            }
            Console.WriteLine($"  ");
        }

        }
    }
