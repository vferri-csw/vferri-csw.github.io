## SAMWebApiSdk

Interfaccia facilitata alla Web API di [Centro Software](https://www.centrosoftware.com/) per il prodotto SAM **ERP2** `6.0`.

Si offre un’esperienza di sviluppo guidata che velocizza i tempi di realizzazione di un software integrato con SAM ERP2, riducendo la probabilità di errori di sintassi rispetto all’utilizzo diretto tramite chiamate HTTP della Web API.

### Installabile come pacchetto NuGet

Configurare il file `.csproj` con il riferimento alla libreria aggiungendo la sezione `ItemGroup` e indicando l'ultima versione disponibile della libreria SamWebApiSdk (l'ultima versione è identificabile consultando i packages presenti in questo repository)``

```c#
<Project Sdk="Microsoft.NET.Sdk">
  <PropertyGroup>
    <OutputType>Exe</OutputType>
    <TargetFramework>net5.0</TargetFramework>
  </PropertyGroup>

  <ItemGroup>
    <PackageReference Include="SamWebApiSdk" Version="1.0.0-alpha10" />
  </ItemGroup>
</Project>
```
