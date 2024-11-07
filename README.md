Slava robotam!

Make Mars great again
using System;

class Program
{
    static void Main()
    {
        // Вывод числа e с точностью до десятых
        double e = Math.E;
        Console.WriteLine($"Число e с точностью до десятых: {Math.Round(e, 1)}");
        
        // Альтернативный способ
        Console.WriteLine($"Число e с точностью до десятых: {e:F1}");
    }
}