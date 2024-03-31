```csharp
using System;

public class CHashtager
{
    public string Name { get; set; } = "Omid";
    public string Role { get; set; } = ".NET Developer, Software Engineer";

    public void SayHi()
    {
        Console.WriteLine("Hello world, I debug life!");
    }
}

class Program
{
    static void Main(string[] args)
    {
        var me = new CHashtager();
        me.SayHi();
    }
}
```
