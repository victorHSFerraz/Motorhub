
## Commands

#### Create a new Web API project 
```
dotnet new webapi -o src/MyWebApi --use-controllers
```

#### Add the project to the solution
```
dotnet sln add src/MyWebApi
```

#### Build the solution
```
dotnet build
```

#### Run the project
```
dotnet watch
```

#### Run docker compose
```
docker compose up -d
```

#### List docker volumes
```
docker volume list
```

#### Remove docker volume
```
docker volume rm <volume-name>
```

#### Create classlib
```
dotnet new classlib -o src/Foo
```

#### Add reference to the project
```
cd src/MyWebApi
dotnet add reference ../Foo
```

#### Add migration
```
dotnet ef migrations add InitialCreate
```

#### Update database
```
dotnet ef database update
```

#### Remove migration
```
dotnet ef migrations remove
```


