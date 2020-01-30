using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication5
{
    class Program
    {
        static void Main(string[] args)
        {
            OldPhotoCopy copy = new OldPhotoCopy();
            PhotoCopyInterface adapter = new TouchScreenAdapter(copy);

            adapter.chooseFirstSelection();
            adapter.chooseSecondSelection();
            Console.ReadLine();
        }
    }
}
