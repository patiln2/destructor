using System;
namespace CSharp_Shell
{
	public class program
	{
		public program()
		{
			Console.WriteLine("constructor called");
		}
		~program()
		{
			Console.WriteLine("destructor called");
		}
			public static void Main()
			{
				program p=new program();
			}
		}
	}
