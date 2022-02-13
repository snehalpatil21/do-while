# do-while
using System;
using System.IO;
using System.Linq;
using System.Collections.Generic;

namespace CSharp_Shell
{

    public class Program 
    {
        public static void Main()
        {
			int i=1,a;
			Console.WriteLine("Enter any number");
			a=Convert.ToInt32(Console.ReadLine());
			Console.WriteLine("The table of given number is:");
			do
			{
				Console.WriteLine(a*i);
				i++;
			}
			while(i<=10);
        }
    }
}
