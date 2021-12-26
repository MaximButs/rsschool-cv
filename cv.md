# **Maxim Butsenko**
## **My contacts:**
 - *Location:* **Minsk, Republic of Belarus**
 - *Telephone:* **+375 25 736 71 19**
 - *Email:* **5683944@mail.ru**
 - *Github:* **[MaximButs](https://github.com/MaximButs)**
 ## **About me:**
 I have good programming skills in languages such as C++, C#, HTML, CSS, JS(basic) and Git. Developed SoftSkills and fast learning.
 ## **Skills**
- C++
- C#
- HTML/CSS
- JavaScript (Basic)
- Git
## **Code Example C#**
CargoTransportation

Program.cs

using System;

namespace Project_1
{
    class Program
    {
        static void Main(string[] args)
        {

            CargoTransport truck1 = new Truck(30, 20, 10, 200, 40, 3);
            truck1.print();
            Console.WriteLine($"Мощность грузовика = {truck1.Power():0.00}");
            Console.WriteLine($"Расстояние (путь) пройденный грузовиком = {truck1.Distance():0.00}");
            Console.WriteLine();
            CargoTransport train1 = new Train();
            train1.print();
            Console.WriteLine($"Мощность поезда = {train1.Power():0.00}");
            Console.WriteLine($"Расстояние (путь) пройденный поездом = {train1.Distance():0.00}");
            Console.WriteLine();
            Train train2 = new Train(35, 27, 11, 351.7, 48.9, 2.3);
            train2.print();
            Console.WriteLine($"Мощность поезда = {train2.Power():0.00}");
            Console.WriteLine($"Расстояние (путь) пройденный поездом = {train2.Distance():0.00}");
            Console.WriteLine();
            Cart cart1 = new Cart();
            cart1.print();
            Console.WriteLine($"Мощность повозки (тележки) = {cart1.Power():0.00}");
            Console.WriteLine($"Расстояние (путь) пройденный повозкой (тележкой) = {cart1.Distance():0.00}");


            Console.ReadKey();
        }
    }
}
## **Experience**
## **Education**
- **University:** Belarusian State University of Informatics and Radioelectronics, Information systems software
- **Courses:** 
  - [learn.epam.com](https://learn.epam.com/myLearning/program?groupGuid=b8907e77-e694-42a9-b845-462c2cb1ad00)
  
## **English**
**A2** (I speak basic English fluently)
