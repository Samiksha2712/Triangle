# Triangle

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp36
{
    class Program
    {
        static void Main(string[] args)
        {
            
            
                string userInput = "";

                bool validMenuSelect = false;

                while (validMenuSelect == false)

                {

                    Console.WriteLine("1 = Enter Triangle Dimensions");
                    Console.WriteLine("2 = Exit\n");

                    Console.WriteLine("Please select an option my entering a number:\n");
                    userInput = Console.ReadLine();


                    if (userInput != "1" && userInput != "2")
                    {
                        Console.WriteLine("Incorrect input given please try again\n ");
                    }
                    if (userInput == "2")
                    {
                        validMenuSelect = true;
                        break;
                    }
                    String a;
                    String b;
                    String c;
                    int Int1;
                    int Int2;
                    int Int3;
                    Console.WriteLine("Enter three integer sides of the triangle\n");

                    do
                    {
                        Console.WriteLine("Enter  value of Int1 ");
                        a = Console.ReadLine();

                    } while (!(int.TryParse(a, out Int1)));



                    do
                    {
                        Console.WriteLine("Enter  value of Int2 ");
                        b = Console.ReadLine();
                    } while (!(int.TryParse(b, out Int2)));

                    do
                    {
                        Console.WriteLine("Enter  value of Int3 \n");
                        c = Console.ReadLine();
                    } while (!(int.TryParse(c, out Int3)));


                    if ((Int1 + Int2) > Int3 && (Int2 + Int3) > Int1 && (Int3 + Int1) > Int2)
                    {
                        Console.WriteLine("Forms a Triangle\n");

                        Console.WriteLine("The three sides of triangle is {0},{1},{2}\n", Int1, Int2, Int3);

                        Console.WriteLine(TriangleSolver.Analyze(Int1, Int2, Int3));
                    }
                    else
                    {
                        Console.WriteLine("Not a triangle\n");
                    }


                }
            }
        }
    }

    

