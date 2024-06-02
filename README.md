```csharp
public Task<IActionResult> PersonalDescription() {
    var profile = new Profile
    {
        Name = "Ezequiel",
        Age = 29,
        Profession = "Software Development Technician",
        Technologies = new List<string> { "C#", ".NET", "SQL SERVER", "JAVASCRIPT", "AND MORE..." }
    };
    
    ViewBag.Welcome = "Welcome to my GitHub!";
    ViewBag.Description = "I'm a Programming Technician with a specialization in .NET technologies.");

    // Enjoy my current projects :)

    return View(profile);
}
```
📫 Do you want to reach me? :link: [ElsBlog (My Blog)](https://www.elsblog.com.ar/) :link: [LinkedIn](https://www.linkedin.com/in/ezemoralesmdp/) :email: `ezemoralesmdp@gmail.com`  
