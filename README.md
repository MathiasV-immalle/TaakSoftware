# TaakSoftware

```
using System;
					
public class Program
{
	private static double KubusVolume(double r)
	{
		double volume = r * r * r;
		return volume;
		
	}
	
	public static void Main()
	{
		double r = 1.2;
		double volume = KubusVolume(1.2);
		Console.WriteLine("De kubus met straal {0} heeft {1} als volume", r, volume);
	}
}
```
