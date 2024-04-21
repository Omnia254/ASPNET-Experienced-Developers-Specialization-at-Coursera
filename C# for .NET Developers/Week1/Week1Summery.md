# Week 1 Summary

## Introduction to .NET Core and its features

.NET (pronounced as "dot net"; formerly named .NET Core) is a free and open-source, managed computer software framework for Windows, Linux, and macOS operating systems.

* **.NET Core Version History**
  * .NET Core 1.0 was released on June 27, 2016, along with Microsoft Visual Studio 2015 Update 3, which enables .NET Core development.
  * .NET Core 2.0 was released on August 14, 2017, along with Visual Studio 2017 15.3, ASP.NET Core 2.0, and Entity Framework Core 2.0

* **Difference Between .NET Framework and .NET Core**
  * .NET is cross-platform and runs on Linux, macOS, and Windows, whereas .NET framework runs only on Windows.
  * .NET is open source and accepts contribution from the community, whereas .NET framework source code is available but restricts direct contribution.

* **Setting up a development environment with Visual Studio and/or VS Code**
  * .NET provides a fast and modular platform for creating many different types of applications that run on Windows, Linux, and macOS.
  * Use Visual Studio Code with the C# and F# extensions to get a powerful editing experience with C# IntelliSense, F# IntelliSense (smart code completion), and debugging.

## Introduction to .NET CLI

The .NET command-line interface (CLI) is a cross-platform toolchain for developing, building, running, and publishing .NET applications.

* **.NET CLI Commands & Platform**
  * Command structure: `dotnet <command> <argument> <option>`
  * All commands start with the driver named `dotnet`.

* **.NET Framework and CLI**
  * .NET Framework includes the Common Language Runtime (CLR) which serves as the execution engine and offers services such as memory management, type safety, exception handling, garbage collection, security, and thread management.
  * Programs written for .NET Framework are compiled into Common Intermediate Language code (CIL), which is then turned into machine code during execution by an architecture-specific just-in-time compiler (JIT).

## CLI Commands

### Basic commands
* `new`
* `restore`
* `build`
* `publish`
* `run`
* `test`
* `vstest`
* `pack`
* `migrate`
* `clean`
* `sln`
* `help`
* `store`
* `watch`
* `format` (Available since .NET 6 SDK)

### Project modification commands
* `add package`
* `add reference`
* `remove package`
* `remove reference`
* `list package`
* `list reference`

### NuGet commands
* `nuget delete`
* `nuget locals`
* `nuget push`
* `nuget add source` (Available since .NET Core 3.1.200 SDK)
* `nuget disable source` (Available since .NET Core 3.1.200 SDK)
* `nuget enable source` (Available since .NET Core 3.1.200 SDK)
* `nuget list source` (Available since .NET Core 3.1.200 SDK)
* `nuget remove source` (Available since .NET Core 3.1.200 SDK)
* `nuget update source` (Available since .NET Core 3.1.200 SDK)
* `nuget verify` (Available since .NET 5 SDK)
* `nuget trust` (Available since .NET 5 SDK)
* `nuget sign` (Available since .NET 6 SDK)
* `package search` (Available since .NET 8.0.2xx SDK)

### Workload management commands
* `workload` (Available since .NET 7 SDK)
* `workload install` (Available since .NET 6 SDK)
* `workload list` (Available since .NET 6 SDK)
* `workload update` (Available since .NET 6 SDK)
* `workload restore` (Available since .NET 6 SDK)
* `workload repair` (Available since .NET 6 SDK)
* `workload uninstall` (Available since .NET 6 SDK)
* `workload search` (Available since .NET 6 SDK)

### Advanced commands
* `sdk check`
* `msbuild`
* `build-server`
* `dev-certs`
* `dotnet install script`

### Tool management commands
* `tool install`
* `tool list`
* `tool update`
* `tool restore`
* `tool run`
* `tool uninstall`
* `tool search`

Tools are console applications installed from NuGet packages and invoked from the command prompt. You can write tools yourself or install tools written by third parties. Tools are also known as global tools, tool-path tools, and local tools.
