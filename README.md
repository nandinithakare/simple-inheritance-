# simple-inheritance-
using System;
Namespace CSharp_Shell
{
Public class Program 
    {
    Public	int rollno=114;
     Public string	name=”Nandini”;
    }
    Class exam:Program
    {
  Public static void Main()
        {
         	Exam n=new exam();
           Console.WriteLine(n.rollno);
           Console.WriteLine( n.name);
        	Console.ReadLine();
        }
    }
}

