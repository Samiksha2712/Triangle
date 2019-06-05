# Triangle - Test cases
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using ConsoleApp36;
using NUnit.Framework;

namespace Test_Triangle
{
    [TestFixture]
    class ConsoleApp36
    {
        [Test]
        public void Analyze_ainput1_binput1_cinput1_output_EquilateralTriangle()
        {
            //Arrange
            int a = 1;
            int b = 1;
            int c = 1;
            String Result = TriangleSolver.Analyze(a, b, c);
            String expectedOutput = Result;

            //Act
            String actualResult = "Equilateral Traingle";



            //Assert
            Assert.AreEqual(expectedOutput, actualResult);


        }

        [Test]
        public void Analyze_ainput200_binput200_cinput10_output_IsoscelesTriangle()
        {
            //Arrange
            int a = 200;
            int b = 200;
            int c = 10;
            String Result = TriangleSolver.Analyze(a, b, c);
            String expectedOutput = Result;

            //Act
            String actualResult = "Isosceles Triangle";



            //Assert
            Assert.AreEqual(expectedOutput, actualResult);



        }
        [Test]
        public void Analyze_ainput3_binput10_cinput15_output_ScaleneTriangle()
        {
            //Arrange
            int a = 3;
            int b = 10;
            int c = 15;
            String Result = TriangleSolver.Analyze(a, b, c);
            String expectedOutput = Result;

            //Act
            String actualResult = "Scalene Triangle";



            //Assert
            Assert.AreEqual(expectedOutput, actualResult);


        }
        [Test]
        public void Analyze_ainput1000_binput1000_cinput1000_output_EquilateralTriangle()
        {
            //Arrange
            int a = 1000;
            int b = 1000;
            int c = 1000;
            String Result = TriangleSolver.Analyze(a, b, c);
            String expectedOutput = Result;

            //Act
            String actualResult = "Equilateral Traingle";



            //Assert
            Assert.AreEqual(expectedOutput, actualResult);

        }
        [Test]
        public void Analyze_ainput45_binput45_cinput30_output_IsoscelesTriangle()
        {
            //Arrange
            int a = 45;
            int b = 45;
            int c = 30;
            String Result = TriangleSolver.Analyze(a, b, c);
            String expectedOutput = Result;

            //Act
            String actualResult = "Isosceles Triangle";



            //Assert
            Assert.AreEqual(expectedOutput, actualResult);

        }
        [Test]
        public void Analyze_ainput8_binput10_cinput5_output_ScaleneTriangle()
        {
            //Arrange
            int a = 8;
            int b = 10;
            int c = 5;
            String Result = TriangleSolver.Analyze(a, b, c);
            String expectedOutput = Result;

            //Act
            String actualResult = "Scalene Triangle";



            //Assert
            Assert.AreEqual(expectedOutput, actualResult);

        }
        [Test]
        public void Analyze_ainput35_binput35_cinput35_output_EquilateralTriangle()
        {
            //Arrange
            int a = 35;
            int b = 35;
            int c = 35;
            String Result = TriangleSolver.Analyze(a, b, c);
            String expectedOutput = Result;

            //Act
            String actualResult = "Equilateral Traingle";



            //Assert
            Assert.AreEqual(expectedOutput, actualResult);

        }
        [Test]
        public void Analyze_ainput30_binput30_cinput3_output_IsoscelesTriangle()
        {
            //Arrange
            int a = 30;
            int b = 30;
            int c = 3;
            String Result = TriangleSolver.Analyze(a, b, c);
            String expectedOutput = Result;

            //Act
            String actualResult = "Isosceles Triangle";



            //Assert
            Assert.AreEqual(expectedOutput, actualResult);

        }
        
    }
}

