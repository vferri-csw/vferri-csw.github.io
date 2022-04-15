## SAMWebApiSdk
![image](https://user-images.githubusercontent.com/51919683/163560020-03da04e5-1a5a-4e46-8626-3a5900837a7f.png)

Interfaccia facilitata alla web API di [Centro Software](https://www.centrosoftware.com/) per il prodotto [SAM ERP2](https://www.centrosoftware.com/prodotti/software-sam-erp2) [^1]

[^1]: Disponibile dalla versione `6.0`.

Offre un’**esperienza** di sviluppo **guidata** che **velocizza** i tempi di realizzazione di un software integrato con SAM ERP2, riducendo la probabilità di errori di sintassi rispetto all’utilizzo diretto tramite chiamate HTTP della Web API.

### Utilizzo

Installabile come pacchetto NuGet modificando il proprio file di progetto `.csproj` aggiungendo la sezione `ItemGroup` con il riferimento alla libreria indicandone l'ultima versione disponibile [^2]

[^2]: IIdentificabile consultando i packages presenti all'interno del repository del prodotto.

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

### Funzionamento

![image](https://csharpcorner-mindcrackerinc.netdna-ssl.com/article/tips-to-write-clean-c-sharp-code/Images/Latest1.gif)
