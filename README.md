# OpdrachtenSoftware: Dotnetfiddles

- Oefening 5.8: Wisselkoers euro - dollar / dollar - euro method
```
using System;
					
public class Program
{
	private static double EuroEquivalent(double dollar)
	{
		double centjes = dollar * 0.91;
		return centjes;
	}
	
	private static double DollarEquivalent(double euro)
	{
		double wissel = euro * 1.0986;
		return wissel;
	}
	public static void Main()
	{
		double dollar = 4000.01;
    	double euro = EuroEquivalent(dollar);
    	Console.WriteLine("{0} dollar is gelijk aan {1} euro", dollar, euro);

    	Console.WriteLine(" ");

    	double euro2 = 3640.01;
    	double dollar2 = DollarEquivalent(euro2);
    	Console.WriteLine("{0} euro is gelijk aan {1} dollar", euro2, dollar2);
	}
}
```

- Oefening 5.9: Volume kubus method
```
using System;
					
public class Program
{
	private static double KubusVolume(double z)
	{
		double volume = z * z * z;
		return volume;
		
	}
	
	public static void Main()
	{
		double z = 1.2;
		double volume = KubusVolume(1.2);
		Console.WriteLine("De kubus met straal {0} heeft {1} als volume", z, volume);
	}
}
```

- Oefening 5.10: Opp. cirkel method
```
using System;
					
public class Program
{
	private static double OppCirkel(double r)
	{
		double opp = r * r * Math.PI;
		return opp;
	}
	
	public static void Main()
	{
		double opp = OppCirkel(1.25);
		Console.WriteLine(opp);
	}
}
```

- Oefening 5.11: Tijd in uren-minuten-seconden naar seconden method
```
using System;
					
public class Program
{
	private static int TijdInSec(int a, int b, int c)
	{
		int Seconden = a * 3600 + b * 60 + c;
		return Seconden;
	}
	
	public static void Main()
	{
		int Seconden = TijdInSec(1, 1, 2);
		Console.WriteLine(Seconden);
	}
}
```

