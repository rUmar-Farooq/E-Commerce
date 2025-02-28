
    dotnet add package Microsoft.EntityFrameworkCore --version 9.0.1
    dotnet add package Microsoft.EntityFrameworkCore.SqlServer --version 9.0.1
    dotnet add package Microsoft.EntityFrameworkCore.Tools --version 9.0.1
    dotnet add package CloudinaryDotNet --version 1.27.2
    dotnet add package System.IdentityModel.Tokens.Jwt --version 8.3.1
    dotnet add package dotenv.net --version 3.2.1
    dotnet add package BCrypt.Net-Next --version 4.0.3

    for those who are using Vs code 
    
    dotnet tool install --global dotnet-ef
     dotnet tool list --global

     for migration in vs code 
     
    dotnet ef migrations add "message"
    dotnet ef database update
