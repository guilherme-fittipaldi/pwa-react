# TDE
- Instalar [Visual Studio Code](https://code.visualstudio.com/) 
- Instalar [SDK do .NET Core](https://dotnet.microsoft.com/download)
- Instale a extensão Ionide no Visual Studio Code

![bd07c97f-4b0e-481d-9893-7bbde24a5935](https://user-images.githubusercontent.com/81246770/121075876-18d75680-c7ac-11eb-923a-c2996fe0c09f.jpg)

- Clone o [repositório](https://youtube.com), decompacte o arquivo para a sua máquina e arraste a pasta para o Visual Studio Code

![WhatsApp Image 2021-06-07 at 16 22 29](https://user-images.githubusercontent.com/81246770/121076292-9bf8ac80-c7ac-11eb-977a-4d3fa75057b2.jpeg)

- Acesse C:\Users\<seu_usuario>\AppData\Roaming\NuGet 
- Arraste o arquivo NuGet.Config para o Visual Studio Code e adicione:
```<?xml version="1.0" encoding="utf-8"?>
<configuration>
  <packageSources>
    <add key="nuget.org" value="https://api.nuget.org/v3/index.json" protocolVersion="3" />
  </packageSources>
</configuration>
```

- Aperte `Ctrl+S`
- Agora aperte `Ctrl+'`
- Dentro do terminal digite:

```
cd TDE 
```

- Depois digite:

```
dotnet run 
```
