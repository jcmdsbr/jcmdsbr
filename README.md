# Hey! let's compile 💻

```bash
cd workspaces && mkdir my-profile && cd my-profile
dotnet new console -n Profile
code .
```

---

```cs
namespace Profile;

    internal class Program
    {
        private static void Main(string[] args)
        {
           var aboutMeBuilder = new AboutMeBuilder()
                .WithBasicInfo(
                    name: "Jean Carlos Moreira da Silva",
                    birthDate: new DateTime(1995, 9, 1),
                    workStartDate: new DateTime(2014, 10, 1),
                    currentEmployer: "5by5 IT Solutions",
                    favoriteStack: ".Net Core/C#",
                    address: new("Araraquara", "São Paulo", "Brazil")
                )
                .WithLanguageSkills(
                    new[] { "C#", "Node with JS/TS", "Python", "Powershell", "Shell", "GoLang", "JAVA" },
                )
                .WithDatabaseSkills(
                    new[] { "SQL Server", "PostgreSQL", "Oracle", "MongoDB", "DynamoDB", "Redis", "Firestore" },
                )
                .WithMessagingSkills(
                    new[] { "RabbitMQ", "SNS", "SQS", "Google Pub/Sub", "Azure Service Bus", "Kafka", "SignalR", "Event Hub", "Cloud events" }
                )
                .WithDevOpsSkills(
                    new[] { "Jenkins", "Azure Pipelines", "Cloud Build", "Spinnaker", "Github Actions" }
                )
                .WithBestPracticeSkills(
                    new[] { "Clean Code", "SOLID", "TDD", "Clean Architecture", "DDD", "Hexagonal Architecture", "Pipes&Filters" }
                )
                .WithCloudProviderSkills(
                    new[] { "AWS", "GCP", "Azure", "OCI" }
                )
                .WithArchitectureDesignSkills(
                    new[] { "Microservices", "Event Sourcing", "CQRS", "EDAs", "CDC", "ACLs", "BFFs / Gateway Aggregation", "Federated Identity", "Cache-Aside" }
                )
                .WithResilienceDesignSkills(
                    new[] { "Retry", "Circuit Breaker", "Fallback", "BulkHead", "Timeout", "SAGA" }
                )
                .WithKnowledgeInSSIS()
                .WithKnowledgeInMultiLanguageApplication()
                .WithKnowledgeInDistributedSystems()
                .WithKnowledgeInServerlessApplication();

            Console.Writeline(aboutMeBuilder.Build());
        }
    }
```

---

```bash
dotnet run Profile.csproj
```

---

- :blush:  Principal Solutions/Sofrware Architecture with over 10 years of experience, I help companies navigate their digital modernization journeys, leveraging technology as a strategic pillar for decision-making and sustainable growth.
- :speech_balloon: Throughout my career, I have worked on challenging projects across various industries, including government, e-commerce, agriculture, aviation, education, and, most recently, healthcare. Each experience has fueled my passion for innovation and impactful solutions.
-  :fire: A recent highlight of my career was my involvement in the second-largest merger between Brazilian companies in 2024, between Hapvida and NotreDame Intermédica, where I contributed to the strategic technological direction, accelerating digital transformation.
-  :yum: My expertise in open-source technologies such as Kubernetes, Helm, Keda, and OpenTelemetry has been instrumental in enabling large organizations to scale and modernize their systems sustainably and efficiently.
-  :hospital: Currently, I am contributing to the strategic and tactical design of solutions at Hapvida NDI, Brazil’s largest healthcare operator, driving innovation and enabling new scenarios to address the challenges of the future.

<h2>
<p align=center>
  <a href="https://github.com/anuraghazra/github-readme-stats" title="Top Langs">
    <img height=175 align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jcmdsbr&layout=compact&theme=gotham">
  </a>
  <a href="https://github.com/anuraghazra/github-readme-stats" title="About Me">
  <img height=175 align="center" src="https://github-readme-stats.vercel.app/api?username=jcmdsbr&show_icons=true&layout=compact&theme=gotham" />
  </a>
</p>
</h2>

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
