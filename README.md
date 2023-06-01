# operators
Patika.Dev Operators
namespace operators;

internal class NewBaseType
{
    static void Main(string[] args)
    {
        // assignment opr
        int a = 1;
        int b = 3;
        b += 2;
        Console.WriteLine(b);

        // logic opr
        bool x = true;
        bool y = false;
        bool z = true;
        Console.WriteLine(x && y);
        Console.WriteLine(x || z);
        Console.WriteLine(x!);

        //relational opr
        int number1 = 6;
        int number2 = 9;

        if (number2 > number1);
        {
            Console.WriteLine("number2 büyük number1'den.");
        }
        if (number1 < number2);
        {
            Console.WriteLine("number1 küçük number2'den.");
        }
        if (number2 == number1);
        {
            Console.WriteLine("number1 eşittir number2'ye.");
        }

        //aritmetic opr
        int n = 8;
        int m = 10;
        Console.WriteLine(m + n);
        Console.WriteLine(m - n);
        Console.WriteLine(m * n);
        Console.WriteLine(m / n);
        Console.WriteLine(m % n);
    }
}
