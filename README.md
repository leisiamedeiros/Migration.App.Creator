# Migration.App.Creator
[![.NET](https://github.com/leisiamedeiros/Migration.App.Creator/actions/workflows/dotnet.yml/badge.svg?branch=release)](https://github.com/leisiamedeiros/Migration.App.Creator/actions/workflows/dotnet.yml)

Create migration files with the fluent migration and versioning

## Usage

Navigate with the command line to the folder where you want the migration file to be created and 
execute the command bellow;

`$ mcreator MigrationName`

## Nuget

[![Nuget](https://img.shields.io/nuget/v/MCreator.Tool)](https://www.nuget.org/packages/MCreator.Tool/) 

```bash
dotnet tool install --global MCreator.Tool --version 1.0.0
```
## Installing this package Locally
Clone this project, navigate with the command line and runs the commands bellow;

Install  
`dotnet tool install --global --add-source ./nupkg Migration.App.Creator`

Uninstall  
`dotnet tool uninstall -g Migration.App.Creator`

# Run your FluentMigrations with Migration.App

If you want to run your FluentMigrations with a WebAPI look into this project [Migration.App](https://github.com/leisiamedeiros/Migration.App)

Enjoy!
