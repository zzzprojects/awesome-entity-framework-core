# Awesome Entity Framework Core

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

Entity Framework Core is a lightweight, extensible and cross-platform object-relational mapper (ORM) made by Microsoft. It is the official data access platform for Microsoft.

A curated list of awesome entity framework core libraries, packages, and documentation.

## Sponsors

ZZZ Projects owns and maintains **Awesome EF Core** as part of our [mission](https://zzzprojects.com/mission) to add value to the .NET community

Through [Entity Framework Extensions](https://entityframework-extensions.net/) and [Dapper Plus](https://dapper-plus.net/), we actively sponsor and help key open-source libraries grow.

[![Entity Framework Extensions](https://raw.githubusercontent.com/zzzprojects/awesome-entity-framework-core/master/entity-framework-extensions-sponsor.png)](https://entityframework-extensions.net/bulk-insert)

[![Dapper Plus](https://raw.githubusercontent.com/zzzprojects/awesome-entity-framework-core/master/dapper-plus-sponsor.png)](https://dapper-plus.net/bulk-insert)

### Contributing

Suggestions and contributions are always welcome! Make sure to read the [contribution guidelines](https://github.com/zzzprojects/awesome-entity-framework-core/blob/master/CONTRIBUTING.md) before submitting a pull request.

### Contents

- [EF Core Newsletter](#ef-core-newsletter)
- [Documentation and Learning](#documentation-and-learning)
- [Popular Packages](#popular-packages)
- [Supported Packages](#supported-packages)
- [Profiler Packages](#profiler-packages)
- [Provider Packages](#provider-packages)
- [Unsupported Packages](#supported-packages)

## EF Core Newsletter

**📬 Subscribe for Entity Framework updates that matter** – [Sign up free](https://mailchi.mp/zzzprojects/entity-framework-newsletter) and stay in the loop.

- 🛠️ Real-world Entity Framework tips
- 🚀 New package releases
- 🎓 Dev-focused video tutorials
- 🧠 Fresh articles and guides

## Documentation and Learning

- [Learn Entity Framework Core ](https://www.learnentityframeworkcore.com/) - Your guide to using the latest version of Microsoft's Object Relational Mapper.
- [Entity Framework Core Tutorial](https://entityframeworkcore.com/) - Learn Entity Framework Core with online examples.
- [entityframeworktutorial.net](http://www.entityframeworktutorial.net/efcore/entity-framework-core.aspx) - Learn Entity Framework using simple yet practical examples on EntityFrameworkTutorial.net
- [Entity Framework Core Docs](https://docs.microsoft.com/en-us/ef/core/) - Official documentation for Entity Framework by Microsoft.
- [RIP Tutorial](https://riptutorial.com/entity-framework-core) - Archived Stack Overflow Documentation (Multi-Language)
- AI (Chat GPT)
   - [ZZZ Code AI](https://zzzcode.ai/answer-question?p1=ef%20core) - Generate instant answer to any EF Core question

## Popular Packages

- [Z.EntityFramework.Extensions.EFCore](https://entityframework-extensions.net/) - EF Extensions is a library that adds high performances bulk extension methods such as BulkInsert, BulkUpdate, BulkDelete, BulkMerge, and more.
- [Z.EntityFramework.Plus.EFCore](https://entityframework-plus.net/) - Entity Framework Plus extends your DbContext with must-haves features: Include Filter, Auditing, Caching, Query Future, Batch Delete, Batch Update, and more
- [Microsoft.EntityFrameworkCore.DynamicLinq](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.DynamicLinq/) - With this library it's possible to write Dynamic LINQ queries (string based) on an IQueryable

## Supported Packages

- [Aspire.Microsoft.EntityFrameworkCore.SqlServer](https://www.nuget.org/packages/Aspire.Microsoft.EntityFrameworkCore.SqlServer/) - Registers EntityFrameworkCore DbContext service for connecting Azure SQL, MS SQL server database. Enables connection pooling, retries, health check, logging and telemetry.
- [Audit.EntityFramework.Core](https://www.nuget.org/packages/Audit.EntityFramework.Core) - Automatically generates audit logs for Entity Framework operations, supporting both Entity Framework and Entity Framework Core.
- [Bricelam.EntityFrameworkCore.Pluralizer](https://www.nuget.org/packages/Bricelam.EntityFrameworkCore.Pluralizer/) - Adds design-time pluralization to EF Core.
- [Clave.Expressionify](https://www.nuget.org/packages/Clave.Expressionify/) - Add expressionify support to Entity Framework Core queries.
- [DelegateDecompiler.EntityFramework](https://www.nuget.org/packages/DelegateDecompiler.EntityFramework/) - A library that is able to decompile a delegate or a method body to their lambda representation.
- [Detached.Mappers.EntityFramework](https://www.nuget.org/packages/Detached.Mappers.EntityFramework/) - Maps Dtos directly to entities already attached to a DbContext. Solves disconnected entities, partial updates and automapping in a single step.
- [EFCore.NamingConventions](https://www.nuget.org/packages/EFCore.NamingConventions/) - Naming Conventions for Entity Framework Core Tables and Columns.
- [EfCoreNexus.Framework](https://www.nuget.org/packages/EfCoreNexus.Framework/) - Integrate the entity framework core into your blazor app with ease and less code.
- [EFCoreSecondLevelCacheInterceptor](https://www.nuget.org/packages/EFCoreSecondLevelCacheInterceptor/) - Second level caching is a query cache. The results of EF commands will be stored in the cache, so that the same EF commands will retrieve their data from the cache rather than executing them against the database again.
- [EfLocalDb](https://www.nuget.org/packages/EfLocalDb/) - Provides a wrapper around the LocalDB to simplify running tests that require Entity Framework.
- [EntityCloner.Microsoft.EntityFrameworkCore](https://www.nuget.org/packages/EntityCloner.Microsoft.EntityFrameworkCore/) - Cloning entities using EntityFrameworkCore configuration.
- [EntityFrameworkCore.AuditInterceptor](https://www.nuget.org/packages/EntityFrameworkCore.AuditInterceptor/) - EntityFrameworkCore.AuditInterceptor is a .NET library designed to provide seamless auditing capabilities for Entity Framework Core.
- [EntityFrameworkCore.ConfigurationManager](https://www.nuget.org/packages/EntityFrameworkCore.ConfigurationManager/) - Extends EF Core to resolve connection strings from App.config.
- [EntityFrameworkCore.Exceptions.MySQL.Pomelo](https://www.nuget.org/packages/EntityFrameworkCore.Exceptions.MySQL.Pomelo/) - Handle database errors easily when working with Entity Framework Core. Supports SQLServer, PostgreSQL, SQLite, Oracle and MySql
- [EntityFrameworkCore.Exceptions.MySQL](https://www.nuget.org/packages/EntityFrameworkCore.Exceptions.MySQL/) - Handle database errors easily when working with Entity Framework Core. Supports SQLServer, PostgreSQL, SQLite, Oracle and MySql
- [EntityFrameworkCore.Exceptions.Oracle](https://www.nuget.org/packages/EntityFrameworkCore.Exceptions.Oracle/) - Handle database errors easily when working with Entity Framework Core. Supports SQLServer, PostgreSQL, SQLite, Oracle and MySql
- [EntityFrameworkCore.Exceptions.PostgreSQL](https://www.nuget.org/packages/EntityFrameworkCore.Exceptions.PostgreSQL/) - Handle database errors easily when working with Entity Framework Core. Supports SQLServer, PostgreSQL, SQLite, Oracle and MySql
- [EntityFrameworkCore.Exceptions.Sqlite](https://www.nuget.org/packages/EntityFrameworkCore.Exceptions.Sqlite/) - Handle database errors easily when working with Entity Framework Core. Supports SQLServer, PostgreSQL, SQLite, Oracle and MySql
- [EntityFrameworkCore.Exceptions.SqlServer](https://www.nuget.org/packages/EntityFrameworkCore.Exceptions.SqlServer/) - Handle database errors easily when working with Entity Framework Core. Supports SQLServer, PostgreSQL, SQLite, Oracle and MySql
- [EntityFrameworkCore.Projectables](https://www.nuget.org/packages/EntityFrameworkCore.Projectables/) - Flexible projection magic for EF Core.
- [EntityFrameworkCore.Scaffolding.Handlebars](https://www.nuget.org/packages/EntityFrameworkCore.Scaffolding.Handlebars/) - Uses Handlebars.NET to compile Handlebars templates when generating models with the Entity Framework Core scaffolding tools.
- [EntityFrameworkCore.Sqlite.NodaTime](https://www.nuget.org/packages/EntityFrameworkCore.Sqlite.NodaTime/) - Adds support for NodaTime types when using SQLite with Entity Framework Core.
- [EntityFrameworkCore.Testing.NSubstitute](https://www.nuget.org/packages/EntityFrameworkCore.Testing.NSubstitute/) - Adds relational support to the Microsoft EntityFrameworkCore in-memory database provider by mocking relational operations.
- [EntityFrameworkCore.Triggers](https://www.nuget.org/packages/EntityFrameworkCore.Triggers/) - Supports events for entity inserting, inserted, updating, updated, deleting, and deleted. Also events on insert failure, update failure, and delete failure.
- [EntityFrameworkCore.VisualBasic](https://www.nuget.org/packages/EntityFrameworkCore.VisualBasic/) - Adds VB design-time support to EF Core.
- [EntityFrameworkExtras.EFCore](https://www.nuget.org/packages/EntityFrameworkExtras.EFCore/) - EntityFrameworkExtras.EFCore provides some useful additions to EntityFramework such as executing Stored Procedures with User-Defined Table Types and Output Parameters.
- [EntityFrameworkRuler.Design](https://www.nuget.org/packages/EntityFrameworkRuler.Design/) - This is a design-time library that interacts with EF Core's reverse engineer (scaffolding) process.
- [ErikEJ.EFCorePowerTools.Cli](https://www.nuget.org/packages/ErikEJ.EFCorePowerTools.Cli/) - Cross platform command line tool for advanced EF Core reverse engineering.
- [ErikEJ.EntityFrameworkCore.DgmlBuilder](https://www.nuget.org/packages/ErikEJ.EntityFrameworkCore.DgmlBuilder/) - Generate DGML (Graph) content that visualizes your DbContext. Adds the AsDgml() extension method to the DbContext class. Also has AsSqlScript() extension method to generate a SQL script for your current model.
- [ErikEJ.EntityFrameworkCore.SqlServer.Dacpac](https://www.nuget.org/packages/ErikEJ.EntityFrameworkCore.SqlServer.Dacpac/) - Reverse engineer a SQL Server .dacpac with the EF Core tooling.
- [Laraue.EfCoreTriggers.Common](https://www.nuget.org/packages/Laraue.EfCoreTriggers.Common/) - EfCoreTriggers is the library to write native SQL triggers using EFCore model builder. Triggers are automatically translating into sql and adding to migrations.
- [LinqKit.Microsoft.EntityFrameworkCore](https://www.nuget.org/packages/LinqKit.Microsoft.EntityFrameworkCore/) - LinqKit.Microsoft.EntityFrameworkCore contains extensions for LINQ to SQL and EntityFrameworkCore. With Include(...) and IDbAsync support.
- [LLL.AutoCompute.EFCore](https://www.nuget.org/packages/LLL.AutoCompute.EFCore/) - Auto updated computed properties for EF Core.
- [MassTransit.EntityFrameworkCore](https://www.nuget.org/packages/MassTransit.EntityFrameworkCore/) - MassTransit provides a developer-focused, modern platform for creating distributed applications without complexity.
- [MockQueryable.EntityFrameworkCore](https://www.nuget.org/packages/MockQueryable.EntityFrameworkCore/) - Extensions for mocking Entity Framework Core (EFCore) operations such ToListAsync, FirstOrDefaultAsync etc. by Moq, NSubstitute or FakeItEasy.
- [Moq.EntityFrameworkCore](https://www.nuget.org/packages/Moq.EntityFrameworkCore/) - This library helps you mocking EntityFramework contexts. Now you will be able to test methods that are using DbSet<TEntity> or DbQuery<TEntity> from DbContext in an effective way.
- [NeinLinq.EntityFrameworkCore](https://www.nuget.org/packages/NeinLinq.EntityFrameworkCore/) - NeinLinq provides helpful extensions for using LINQ providers such as Entity Framework that support only a minor subset of .NET functions, reusing functions, rewriting queries, even making them null-safe, and building dynamic queries using translatable predicates and selectors.
- [Npgsql.EntityFrameworkCore.PostgreSQL](https://www.nuget.org/packages/Npgsql.EntityFrameworkCore.PostgreSQL/) - Npgsql.EntityFrameworkCore.PostgreSQL is the open source EF Core provider for PostgreSQL.
- [Pagination.EntityFrameworkCore.Extensions](https://www.nuget.org/packages/Pagination.EntityFrameworkCore.Extensions/) - This is a library for List Pagination on Dotnet. Works well with Entity Framework as an extension.
- [SimplerSoftware.EntityFrameworkCore.SqlServer.NodaTime](https://www.nuget.org/packages/SimplerSoftware.EntityFrameworkCore.SqlServer.NodaTime/) - Adds native support to EntityFrameworkCore for SQL Server for the NodaTime types.
- [Toolbelt.EntityFrameworkCore.IndexAttribute](https://www.nuget.org/packages/Toolbelt.EntityFrameworkCore.IndexAttribute/) - The [IndexColumn] attribute that is the revival of [Index] attribute for EF Core. (with extension for model building.)
- [Verify.EntityFramework](https://www.nuget.org/packages/Verify.EntityFramework/) - Extends Verify to allow snapshot testing with EntityFramework.
- [Zomp.EFCore.WindowFunctions.SqlServer](https://www.nuget.org/packages/Zomp.EFCore.WindowFunctions.SqlServer/) - Window functions for SQL Server database provider for Entity Framework Core.

## Profiler Packages
- [Hibernating Rhinos Entity Framework Profiler](https://hibernatingrhinos.com/products/efprof) - Entity Framework Profiler is a real-time visual debugger allowing a development team to gain valuable insight and perspective into their usage of Entity Framework.
- [MiniProfiler.EntityFrameworkCore](https://miniprofiler.com) - A simple but effective mini-profiler for .NET, Ruby, Go and Node.js.
- [EFCore.Visualizer](https://marketplace.visualstudio.com/items?itemName=GiorgiDalakishvili.EFCoreVisualizer) - View Entity Framework Core query plan directly in Visual Studio.
 
## Providers	

- [Microsoft.EntityFrameworkCore.SqlServer](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/) - Microsoft.EntityFrameworkCore.SqlServer is the EF Core database provider package for Microsoft SQL Server and Azure SQL.
- [Microsoft.EntityFrameworkCore.Sqlite](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Sqlite/) - Microsoft.EntityFrameworkCore.Sqlite is the EF Core database provider package for SQLite.
- [Microsoft.EntityFrameworkCore.InMemory](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.InMemory/) - Microsoft.EntityFrameworkCore.InMemory is the EF Core database provider package for the built-in in-memory database.
- [EntityFrameworkCore.Jet](https://www.nuget.org/packages/EntityFrameworkCore.Jet/) - Jet/ACE database provider for Entity Framework Core (Microsoft Access MDB/ACCDB files).
- [FirebirdSql.EntityFrameworkCore.Firebird](https://www.nuget.org/packages/FirebirdSql.EntityFrameworkCore.Firebird/) - The Entity Framework Core provider for Firebird enables you to develop .NET applications that connect to the Firebird database using Entity Framework Core.
- [IBM.EntityFrameworkCore](https://www.nuget.org/packages/IBM.EntityFrameworkCore) - IBM.EntityFrameworkCore is a NuGet package that serves as the IBM Data Server provider for Entity Framework Core, enabling .NET applications to interact seamlessly with IBM database servers.
- [MySql.EntityFrameworkCore](https://www.nuget.org/packages/MySql.EntityFrameworkCore/) - MySQL provides connectivity for client applications developed in .NET compatible programming languages with MySQL Connector/NET through a series of packages.
- [Npgsql.EntityFrameworkCore.PostgreSQL](https://www.nuget.org/packages/Npgsql.EntityFrameworkCore.PostgreSQL/) - Npgsql.EntityFrameworkCore.PostgreSQL is the open source EF Core provider for PostgreSQL. It allows you to interact with PostgreSQL via the most widely-used .NET O/RM from Microsoft, and use familiar LINQ syntax to express queries. It's built on top of Npgsql.
- [Pomelo.EntityFrameworkCore.MySql](https://www.nuget.org/packages/Pomelo.EntityFrameworkCore.MySql/) - omelo.EntityFrameworkCore.MySql is the Entity Framework Core (EF Core) provider for MySQL, MariaDB, Amazon Aurora, Azure Database for MySQL and other MySQL-compatible databases.
- [Devart.Data.MySql.EFCore](https://www.nuget.org/packages/Devart.Data.MySql.EFCore/) - dotConnect for MySQL is a high-performance ORM enabled data provider for MySQL 8.0+ including Embedded servers (starting with 4.1), MariaDB, Amazon RDS, Amazon Aurora, Azure MySQL, Percona that builds on ADO.NET technology.
- [Devart.Data.Oracle.EFCore](https://www.nuget.org/packages/Devart.Data.Oracle.EFCore/) - dotConnect for Oracle is a high-performance ORM enabled data provider for Oracle and Oracle Cloud (DBaaS) that builds on ADO.NET technology.
- [Devart.Data.PostgreSql.EFCore](https://www.nuget.org/packages/Devart.Data.PostgreSql.EFCore/) - dotConnect for PostgreSQL is a high-performance ORM enabled data provider for PostgreSQL that builds on ADO.NET technology.
- [Devart.Data.SQLite.EFCore](https://www.nuget.org/packages/Devart.Data.SQLite.EFCore/) - dotConnect for SQLite is a high-performance ORM enabled data provider for SQLite that builds on ADO.NET technology.

## Unsupported Packages	

_We no longer list unsupported packages. There are too many!_

## More Projects

- Projects:
   - [EntityFramework Extensions](https://entityframework-extensions.net/)
   - [Dapper Plus](https://dapper-plus.net/)
   - [C# Eval Expression](https://eval-expression.net/)
- Learn Websites
   - [Learn EF Core](https://www.learnentityframeworkcore.com/)
   - [Learn Dapper](https://www.learndapper.com/)
- Online Tools:
   - [.NET Fiddle](https://dotnetfiddle.net/)
   - [SQL Fiddle](https://sqlfiddle.com/)
   - [ZZZ Code AI](https://zzzcode.ai/)
- and much more!

To view all our free and paid projects, visit our website [ZZZ Projects](https://zzzprojects.com/).
