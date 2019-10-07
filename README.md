# LabOne-2
using System;

namespace LabOne_2
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello! Selest time o'clock second");
            string s = Console.ReadLine();
            int second = Convert.ToInt32(s);
            int hour = second / 3600;
            int minute = (second - hour*3600) / 60;
            Console.WriteLine("Hour= "+hour);
            Console.WriteLine("Minute= " + minute);
           
            
            Console.ReadLine();
            
        }
    }
}
