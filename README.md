using System.Threading;
class task6
{
    public static void Main(String[] args)
    {
        Console.WriteLine();
        Console.ForegroundColor = ConsoleColor.Magenta;
        Console.WriteLine("                     Lift operation");
        Console.WriteLine("────────────────────────────────────────────────────────────────────────────────");
        Console.WriteLine("Total floor in appartment -- 5 (from 1 to 5)");
        Console.Write("Which floor you wish to go : ");
        int n = Convert.ToInt16(Console.ReadLine());
        Console.WriteLine();
        int a;
        while(n > 5)
        {
            Console.WriteLine("INVALID INPUT");
            Console.Write("Which floor you wish to go : ");
            n = Convert.ToInt16(Console.ReadLine());

        }

        switch (n)
        {
            case 1:

                Console.WriteLine("1-Floor arrived");
                Console.Write("Which floor you wish to go next : ");
                a = Convert.ToInt16(Console.ReadLine());
                if (a == 2)
                {
                    Console.WriteLine();
                    Console.WriteLine("1-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor arrived");
                }
                else if(a==3)
                {
                    Console.WriteLine("1-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor arrived");
                }
                else if(a==4)
                {
                    Console.WriteLine("1-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor arrived");
                }
                else if(a==5)
                {
                    Console.WriteLine("1-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("5-Floor arrived");

                }
                break;
            case 2:
                
                Console.WriteLine("1-Floor arrived");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("1-Floor departed");
                Thread.Sleep(1000);
                Console.Clear();
                Console.WriteLine("2-Floor arrived");
                Console.Write("Which floor you wish to go ");
                a = Convert.ToInt16(Console.ReadLine());
                if (a==1)
                {
                    Console.WriteLine("1-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("1-Floor arrived");
                }
                else if(a==3)
                {
                    Console.WriteLine("2-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor arrived");
                }
                else if(a==4)
                {
                    Console.WriteLine("2-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor arrived");
                }
                else if(a==5)
                {
                    Console.WriteLine("2-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("5-Floor arrived");

                }
                break;
            case 3:
                Console.WriteLine("1-Floor arrived");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("1-Floor departed");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("2-Floor arrived");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("2-Floor departed");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("3-Floor arrived"); 
                Console.Write("Which floor you wish to go ");
                a = Convert.ToInt16(Console.ReadLine());
                if (a == 1)
                {
                    Console.WriteLine("2-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("1-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("1-Floor arrived");
                }
                else if (a == 2)
                {
                    Console.WriteLine("2-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor arrived");
                }
                else if (a == 4)
                {
                    Console.WriteLine("3-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor arrived");
                }
                else if (a == 5)
                {
                    
                    Console.WriteLine("3-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("5-Floor arrived");
                }
                break;
            case 4:
                Console.WriteLine("1-Floor arrived");
                Thread.Sleep(1000);
                Console.Clear();
                Console.WriteLine("1-Floor departed");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("2-Floor arrived");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("2-Floor departed");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("3-Floor arrived");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("3-Floor departed");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("4-Floor arrived");
                Console.Write("Which floor you wish to go next : ");
                a = Convert.ToInt16(Console.ReadLine());
                if(a==1)
                {
                    Console.WriteLine("3-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("1-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("1-Floor arrived");
                }
                else if(a==2)
                {
                    Console.WriteLine("3-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor arrived");
                }
                else if(a==3)
                {
                    Console.WriteLine("3-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor arrived");
                }
                else if(a==5)
                {
                    Thread.Sleep(1000);
                    Console.Clear();
                    Console.WriteLine("4-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("5-Floor arrived");
                }
                break;
            case 5:
                Console.WriteLine("1-Floor arrived");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("1-Floor departed");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("2-Floor arrived");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("2-Floor departed");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("3-Floor arrived");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("3-Floor departed");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("4-Floor arrived");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("4-Floor departed");
                Thread.Sleep(2000);
                Console.Clear();
                Console.WriteLine("5-Floor arrived");
                a = Convert.ToInt16(Console.ReadLine());
                Console.WriteLine();
                if(a==1)
                {
                    
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("1-Floor arrived");
                }
                else if(a==2)
                {
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("2-Floor arrived");
                    
                }
                else if(a==3)
                {
                    Console.Clear();
                    Console.WriteLine("4-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor arrived");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("3-Floor arrived");
                }
                else if(a==4)
                {
                    
                    Console.Clear();
                    Console.WriteLine("4-Floor departed");
                    Thread.Sleep(2000);
                    Console.Clear();
                    Console.WriteLine("4-Floor arrived");
                }
                break;
          
        }
        Console.WriteLine();
    }
}
