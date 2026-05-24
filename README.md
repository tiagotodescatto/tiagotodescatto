<h2>Hello! I'm Tiago! Here is some of my characteristics <img width="40" alt="image" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3NxbWFlZzhmZXI0aWt3d3puOWtkZmMzOHZnNHU0Y3U0d3JrOWdheCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/WUlplcMpOCEmTGBtBW/giphy.gif"/></h2> 


[![Linkedin: t](https://img.shields.io/badge/-tiagotodescatto-blue?style=flat-square&logo=Linkedin&logoColor=white&https://www.linkedin.com/in/tiago-todescatto-garces-de-oliveira-5b974039b/)](https://www.linkedin.com/in/tiago-todescatto-garces-de-oliveira-5b974039b/)
[![GitHub Thaiane](https://img.shields.io/github/followers/tiagotodescatto?label=follow&style=social)](https://github.com/tiagotodescatto)

<p >
  
  ```C#
  using System;
  using System.Collections.Generic;

  namespace tiago{
    public record TiagoTodescatto(
      string Name,
      List<string> Languages,
      List<string> Interests,
      List<string> Qualities
    );

  class Program{
    static void main(){
      var Tiago = new TiagoTodescatto(
        "Tiago Todescatto Garces de Oliveira",
        new List<string>{ "C#", "C++", "Python" }, // Always learning more about this universe!
        new List<string>{ "Mathematics", "Physics", "Metal Music", "Literature" },
        new List<string>{ "Ethical", "Hardworking", "Creative", "Mature", "Desire for learning new things" }
      );
      Console.WriteLine(Tiago);
      }
    }
  }
```
</p>
