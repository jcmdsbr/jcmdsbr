# Hey! let's compile 💻

```bash
cd workspaces && mkdir my-profile && cd my-profile
dotnet new console -n Profile
code .
```

---

```cs
namespace Profile
{
    internal class Program
    {
        private static void Main(string[] args)
        {
           Console.Writeline(new AboutMeBuilder()
              .WhatIsYourName("Jean Carlos Moreira da Silva")
              .WhatIsYourBirthDate(new DateTime(1995,9,1))
              .WhenDidYouStartWorking(new DateTime(2014,10,1))
              .WhereDoYouWork("5by5 Soluções em Sistemas")
              .WhatIsYourFavoriteStack(".Net Core/C#")
              .WhereYouLive(new Address("Matão", "São Paulo", "Brazil"))
              .WhatAreYourSkillsInLanguages("C#", "Typescript", "Javascript", "Python", "Powershell", "Shell")
              .WhatAreYourSkillsInFrameworks(".Net Core", "Node", "Nest", "Angular", "Rebus", "Ionic")
              .WhatAreYourSkillsInLibraries("React", "Vue", "Express", "AutoMapper", "MediatoR")
              .WhatAreYourSkillsInDatabases("SQL Server", "PostgreSQL", "MongoDB", "DynamoDB", "Redis", "Firestore")
              .WhatAreYourSkillsInORMs("EF", "NHibernate", "Dapper", "TypeORM", "Mongoose")
              .WhatAreYourSkillsInMessageBrokers("RabbitMQ", "SNS", "SQS", "Google Pub/Sub", "Azure Service Bus")
              .WhatAreYourSkillsInDevOpsTools("Jenkins", "Azure Pipelines", "Github Actions", "Spinnaker", "Terraforms")
              .WhatAreYourSkillsInBestPractices("Clean Code", "SOLID", "TDD", "Clean Architecture", "DDD")
              .WhatAreYourSkillsInCloudProviders("AWS", "GCP", "Azure")
              .WhatAreYourSkillsInArchitectureDesignPatterns("Hexagonal", "MicroServices", "Event Sourcing", "CQRS")
              .WhatAreYourSkillsInResilienceDesignPatterns("Retry", "Circuit Breaker", "Fallback", "Timeout", "SAGA")
              .HasKnowledgeInSSIS()
              .HasKnowledgeInMultiLanguageApplication()
              .HasKnowledgeInDistributedSystems()
              .HasKnowledgeInServerlessApplication()
              .Build());
        }
    }
}
```

---

```bash
dotnet run Profile.csproj
```

---

- :blush: Meu nome é Jean Carlos, atualmente atuo como Arquiteto de Software na empresa 5by5 Soluções em Sistemas
- :stuck_out_tongue_closed_eyes: Estou sempre estudando sobre Cloud cloud e novas tecnologias.
- :speech_balloon: Pergunte-me sobre  SOLID, DDD, Clean Code, DevOps, Sistemas Distribuídos, Micro-serviços e Cultura Nerd
- :yum: Desenvolvo a mais de 6 anos em C# como linguagem principal e preferida !!

<h2>

<p align="center">
  <a href="https://twitter.com/jcmdsbr">
  <img  src="https://img.shields.io/twitter/follow/jcmdsbr?color=%231DA1F2&amp;label=Follow%20me&amp;logo=Twitter&amp;style=for-the-badge" alt="Twitter Follow"></a> 
  <a href="https://linkedin.com/in/jcmdsbr"><img src="https://img.shields.io/badge/Follow%20me%20-blue?style=for-the-badge&logo=Linkedin" alt="Linkedin Follow"></a> 
  <a href="https://instagram.com/jcmdsbr"><img src="https://img.shields.io/badge/Follow%20me%20-black?style=for-the-badge&logo=Instagram&logoColor=%231DA1F2" alt="Instagram Follow"></a>
  <a href="https://dev.to/jcmdsbr">
  <img src="https://d2fltix0v2e0sb.cloudfront.net/dev-badge.svg" alt="Jean Carlos's DEV Community Profile" height="30" width="30">
  </a>
  <a href="https://app.rocketseat.com.br/me/jcmdsbr">
  <img src="https://img.shields.io/static/v1?label=Blog&message=Rocketseat&color=7159c1&style=for-the-badge&logo=ghost"/> 
  </a>
</p>

<p align=center>
  <a href="https://github.com/anuraghazra/github-readme-stats" title="Top Langs">
    <img height=175 align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jcmdsbr&layout=compact&theme=gotham">
  </a>
  <a href="https://github.com/anuraghazra/github-readme-stats" title="About Me">
  <img height=175 align="center" src="https://github-readme-stats.vercel.app/api?username=jcmdsbr&show_icons=true&layout=compact&theme=gotham" />
  </a>
</p>

</h2>
