# Awesome Entity Framework Core

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

Entity Framework Core is a lightweight, extensible and cross-platform object-relational mapper (ORM) made by Microsoft. It is the official data access platform for Microsoft.

A curated list of awesome entity framework core libraries, packages, and documentation.

### Contributing

Suggestions and contributions are always welcome! Make sure to read the <a href="https://github.com/zzzprojects/awesome-entity-framework-core/blob/master/CONTRIBUTING.md">contribution guidelines</a> for more information before submitting a pull request.

#### *If you see a package here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

- [Awesome Entity Framework Core](#awesome-entity-framework-core)
   - [Documentation and Learning](#documentation-and-learning)
   - [Popular Packages](#popular-packages)
   - [Supported Packages](#supported-packages)
   - [Profiler Packages](#profiler-packages)
   - [Provider Packages](#provider-packages)
   - [Unsupported Packages](#supported-packages)

## Documentation and Learning

- [Entity Framework Core Docs](https://docs.microsoft.com/en-us/ef/core/) - Official documentation for Entity Framework by Microsoft.
- [Entity Framework Core Tutorial](http://entityframeworkcore.com/) - Learn Entity Framework Core with online examples.
- [entityframeworktutorial.net](http://www.entityframeworktutorial.net/efcore/entity-framework-core.aspx) - Learn Entity Framework using simple yet practical examples on EntityFrameworkTutorial.net
- [Learn Entity Framework Core ](https://www.learnentityframeworkcore.com/) - Your guide to using the latest version of Microsoft's Object Relational Mapper.
- [Knowledge Base - Entity Framework Core](https://entityframeworkcore.com/knowledge-base) - Translated posts from Stack Overflow
- [RIP Tutorial](https://riptutorial.com/entity-framework-core) - Archived Stack Overflow Documentation (Multi-Language)
- [Google](http://www.letmegooglethat.com/?q=Entity+Framework+Core) - Up-and-coming search engine ;)
- Books
    - [Entity Framework Core Cookbook, 2nd Edition](http://shop.oreilly.com/product/9781785883309.do) - Leverage the full potential of Entity Framework with this collection of powerful and easy-to-follow recipes
   - [Mastering Entity Framework Core 2.0](http://shop.oreilly.com/product/9781788294133.do) - Dive into entities, relationships, querying, performance optimization, and more, to learn efficient data-driven development
- Videos
   - [Pluralsight](https://www.pluralsight.com/courses/entity-framework-core-2-getting-started) - This course helps those with experience in earlier versions of EF and EF Core, and developers completely new to Entity Framework.
   - [Channel 9](https://channel9.msdn.com/Events/Build/2018/BRK2144) - Entity Framework Core 2.1: Simple, Powerful Data Access for .NET

## Popular Packages
- [Z.EntityFramework.Extensions.EFCore](https://entityframework-extensions.net/) - Entity Framework Extensions extends your DbContext with high-performance bulk operations: BulkSaveChanges, BulkInsert, BulkUpdate, BulkDelete, BulkMerge, and more.
- [Z.EntityFramework.Plus.EFCore](https://entityframework-plus.net/) - Improves Entity Framework performance and overcomes limitations with MUST-HAVE features.
- [LinqKit.Microsoft.EntityFrameworkCore](https://github.com/scottksmith95/LINQKit) - LINQKit is a free set of extensions for LINQ to SQL and Entity Framework power users.

## Supported Packages
- [Audit.EntityFramework.Core](https://github.com/thepirat000/Audit.NET/tree/master/src/Audit.EntityFramework) - Audit.EntityFramework provides the infrastructure to log interactions with the EF DbContext.
- [DelegateDecompiler.EntityFrameworkCore](https://github.com/hazzik/DelegateDecompiler) - A library which is able to decompile a delegate or a method body to its lambda representation.
- [EntityFrameworkCore.Triggers](https://github.com/NickStrupat/EntityFramework.Triggers) -Adds events for entity inserting, inserted, updating, updated, deleting, and deleted.
- [EntityFrameworkCore.TypedOriginalValues](https://github.com/NickStrupat/EntityFramework.TypedOriginalValues) - Get typed access to the DbEntityEntry<T>.OriginalValues property bag.
- [FlexLabs.Upsert](https://github.com/artiomchi/FlexLabs.Upsert) - Brings UPSERT functionality to common database providers for Entity Framework in their respective native SQL syntax.
- [Microsoft.EntityFrameworkCore.AutoHistory](https://github.com/arch/AutoHistory) - A plugin for Microsoft.EntityFrameworkCore to support automatically recording data changes history.
- [Microsoft.EntityFrameworkCore.DynamicLinq](https://github.com/StefH/System.Linq.Dynamic.Core) - A .NET Core / Standard port of the Microsoft assembly for the .Net 4.0 Dynamic language functionality.
- [Moq.EntityFrameworkCore](https://github.com/MichalJankowskii/Moq.EntityFrameworkCore) - This library helps you with mocking EntityFramework contexts.
- [MockQueryable.Core](https://github.com/romantitov/MockQueryable) - Moking Entity Framework Core operations such ToListAsync, FirstOrDefaultAsync.

## Profiler Packages
- [Hibernating Rhinos Entity Framework Profiler](https://www.hibernatingrhinos.com/products/EFProf) - Entity Framework Profiler is a real-time visual debugger allowing a development team to gain valuable insight and perspective into their usage of Entity Framework.
- [MiniProfiler.EntityFrameworkCore](https://miniprofiler.com) - A simple but effective mini-profiler for .NET, Ruby, Go and Node.js.
 
## Providers	
- [Microsoft.EntityFrameworkCore.SqlServer](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/) - Microsoft SQL Server database provider for Entity Framework Core.
- [Microsoft.EntityFrameworkCore.Sqlite](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Sqlite/) - SQLite database provider for Entity Framework Core.
- [Microsoft.EntityFrameworkCore.InMemory](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.InMemory/) - In-memory database provider for Entity Framework Core (to be used for testing purposes).
- [EntityFrameworkCore.FirebirdSQL](https://github.com/ralmsdeveloper/EntityFrameworkCore.FirebirdSQL) - FirebirdSQL database provider for Entity Framework Core.
- [EntityFrameworkCore.Jet](https://github.com/bubibubi/EntityFrameworkCore.Jet) - Entity Framework Core provider for Access database.
- [EntityFrameworkCore.SqlServerCompact40](https://github.com/ErikEJ/EntityFramework.SqlServerCompact) - Entity Framework Core SQL Server Compact provider.
- [FirebirdSql.EntityFrameworkCore.Firebird](https://www.nuget.org/packages/FirebirdSql.EntityFrameworkCore.Firebird/) -The .NET Data provider is written in C# and provides a high-performance, native implementation of the Firebird API.
- [IBM.EntityFrameworkCore](https://www.nuget.org/packages/IBM.EntityFrameworkCore) - Creating an Entity Data Model using IBM Data Server providers for Entity Framework Core.
- [MySql.Data.EntityFrameworkCore](https://www.nuget.org/packages/MySql.Data.EntityFrameworkCore) - MySql.Data.EntityFrameworkCore for Entity Framework.
- [Npgsql.EntityFrameworkCore.PostgreSQL](https://github.com/npgsql/Npgsql.EntityFrameworkCore.PostgreSQL) - Entity Framework Core provider for PostgreSQL.
- [Pomelo.EntityFrameworkCore.MySql](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql) - Entity Framework Core provider for MySql built on top of mysql-net/MySqlConnector.
- [Devart.Data.Oracle.EFCore](https://www.nuget.org/packages/Devart.Data.Oracle.EFCore/) - A commercial third-party provider for Oracle.
- [Devart.Data.PostgreSql.EFCore](https://www.nuget.org/packages/Devart.Data.PostgreSql.EFCore/) - Entity Framework Core provider for PostgreSQL.
- [Devart.Data.SQLite.EFCore](https://www.nuget.org/packages/Devart.Data.SQLite.EFCore/) - A commercial third-party provider for PostgreSql.
- [Devart.Data.MySql.EFCore](https://www.nuget.org/packages/Devart.Data.MySql.EFCore/) - A commercial third-party provider for MySql.	

## Unsupported Packages	
- [EntityFrameworkCore.Scaffolding.Handlebars](https://github.com/TrackableEntities/EntityFrameworkCore.Scaffolding.Handlebars) - Scaffold EF Core models using Handlebars templates.
- [ReflectionIT.Mvc.Paging](https://github.com/sonnemaf/ReflectionIT.Mvc.Paging) - ASP.NET Core 2.1 MVC Paging (including filtering and sorting) solution using Entity Framework Core 2.0 and IEnumerable<T>.
- [REstate.Engine.Repositories.EntityFrameworkCore](https://github.com/psibr/REstate) - Entity Framework Core repository for REstate Machines and Schematics.	
- [Snickler.EFCore](https://github.com/snickler/EFCore-FluentStoredProcedure) - EFCore Extension that allows a means to map a stored procedure to a class, fluently.
