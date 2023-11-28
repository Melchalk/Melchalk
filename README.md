```c#
namespace Life;

public class Mel
{
   public string Name { get; } =
"Marina Melnikova";
   public int Age { get; private set; } = 18;
   public string Status { get; set; } = "Student";

   public List<string> Skills { get; set; } = new()
      {
        ".Net",
        "SQL",
        "EF Core",
        "OOP",
        "N-Unit",
      };
}
```
