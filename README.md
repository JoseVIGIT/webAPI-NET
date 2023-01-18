# webAPI-NET
Ejemplo webAPI en .NET

## Paso 1: Crear proyecto wepAPI y prueba inicial

En la consola:
```
    dotnet new webapi -o webAPI
```
Creadas las carpetas siguientes:
```
webapi
    /Controllers
    /Properties
    appsettings.Development.json
    appsettings.json
    Program.cs
    WeatherForecast.cs
    webAPI.csproj
```
Estando en la carpeta webAPI.
Ejecutar aplicación:
```
    dotnet run

    Compilando...
    info: Microsoft.Hosting.Lifetime[14]
        Now listening on: http://localhost:5036
    info: Microsoft.Hosting.Lifetime[0]
        Application started. Press Ctrl+C to shut down.
    info: Microsoft.Hosting.Lifetime[0]
        Hosting environment: Development
    info: Microsoft.Hosting.Lifetime[0]
        Content root path: ...
```

El mensaje anterior se muestra la URL base de acceso.
En el navegador:
```
    http://localhost:5036/weatherForecast
```
Si es necesario, cambiar el puerto por el que se muestre al lanzar la ejecución

Resultado:
```
    [{"date":"2023-01-19","temperatureC":26,"temperatureF":78,"summary":"Balmy"},{"date":"2023-01-20","temperatureC":-16,"temperatureF":4,"summary":"Mild"},{"date":"2023-01-21","temperatureC":-17,"temperatureF":2,"summary":"Balmy"},{"date":"2023-01-22","temperatureC":-1,"temperatureF":31,"summary":"Cool"},{"date":"2023-01-23","temperatureC":-12,"temperatureF":11,"summary":"Hot"}]
```  

De vuelta a la consola para detener la ejeción con CTRL+C
