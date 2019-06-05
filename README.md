# Triangle - Class TriangleSolver


using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp36
{
     public static class TriangleSolver
    {
        public static string Analyze(int n1,int n2, int n3)
        {
            Console.WriteLine(" Type of traingle \n");
            if ((n1 == n2 && n2 == n3 && n3 == n1))
            {
                return ("Equilateral Traingle");
                
            }
            else if (n1 != n2 && n2 != n3 && n3 != n1)

            {
                return ("Scalene Triangle");
                
            }
            else if (n1 == n2 || n2 == n3 || n3 != n1)
            {
                return ("Isosceles Triangle");
             
            }
            else
            {
                return  "Null";
            }

           
         

        }
    }
}


    

