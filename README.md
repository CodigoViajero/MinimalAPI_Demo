***************** Minimal API sample in .NET & Docker *****************

This is a Minimal API sample in .NET, just to show how to run and execute CRUD operations thorugh different HTTP endpoints such as GET, POST, PUT, PATCH & DELETE.

It also has a basic JWT bearer authentication.

* Apis/ProductApi.cs file contains all the request the API through the different verbs.
* Data folder contains DBContext, repository and fluentApi validations.
* There's a migration folder with all genrated migrations.
* Validator folder containng Fluent Validation.
* Dtos folder for mapping incomming objects with AutoMapper.
* Dockerfile.
* appSetting.Devopment.json file with Sql Server ConnectionString just for local running.
* appSetting.json with Sql Server ConnectionString when deployed in Docker and JWT values.
  
Execution:

* Dotnet run for local test.
* Docker run following all the commands in Comandos.txt file, including Sql Server.
