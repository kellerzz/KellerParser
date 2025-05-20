<div id="top">

<p align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://i.imgur.com/QRlCrO3.png">
  <source media="(prefers-color-scheme: light)" srcset="https://i.imgur.com/QRlCrO3.png">
  <img alt="ReadmeAI Logo" src="https://i.imgur.com/QRlCrO3.png" width="60%">
</picture>

</p>

<p align="center">
  <em>Pensado e realizado em prol da comunidade de FreeFire, por KellerSS.</em>
</p>



</div>

<img src="https://i.imgur.com/NnWf7Fm.png" alt="line break" width="100%" height="3px">


## Introdução

KellerParser é uma ferramenta poderosa criada para processar e analisar eventos coletados pelo MFTECMD de Eric Zimmerman.

**Por que usar o KellerParser?**

O KellerParser tem como objetivo principal reestruturar e enriquecer os dados coletados, corrigindo automaticamente a data/hora UTC para o horário de Brasília, facilitando sua análise e interpretação.

* **🔵 Facilidade:** Automatiza todo o processo técnico, desde a leitura dos arquivos até a conversão dos horários, sem que você precise fazer nada manualmente.
* **⚡ Agilidade:** Processa grandes volumes de dados rapidamente, economizando horas do seu tempo em análises forenses.
* **🔍 Precisão:** Corrige os timestamps de forma confiável, garantindo que seus relatórios reflitam o horário local correto, essencial para investigações precisas.
* **📂 Organização:** Renomeia e organiza arquivos automaticamente, facilitando o gerenciamento e a rastreabilidade dos seus dados.


## Como utilizar?



#### <img width="2%" src="https://simpleicons.org/icons/diagramsdotnet.svg">&emsp13; Faça o download da DLL:


| Aplicativo                  | Descrição                |
|----------------------------|---------------------------|
| [Parser](https://github.com/kellerzz/KellerParser/raw/refs/heads/main/KellerParser.exe) | Parser  utilizado   |


#### <img width="2%" src="https://simpleicons.org/icons/termius.svg">&emsp13; Utilize MFTECmd para parsear:
```sh
❯ MFTECmd.exe -f c:\$MFT --csv . --csvf "kellerssMFT %USERNAME%.csv" && MFTECmd.exe -f "C:\$Extend\$UsnJrnl:$J" --csv . --csvf "kellerssUSN %USERNAME%.csv"

```

#### <img width="2%" src="https://simpleicons.org/icons/termius.svg">&emsp13; Coloque os .cvs na mesma pasta do parser e execute ele como administrador.


#### <img width="2%" src="https://simpleicons.org/icons/termius.svg">&emsp13; Após parsear, ele irá mover os .cvs utilizados para uma outra pasta e restará somente os corrigidos na pasta principal.




<img src="https://i.imgur.com/NnWf7Fm.png" alt="line break" width="100%" height="3px">

## Contribuições

Contribuições são bem vindas! Por favor me chame no privado do discord `keller22cao`.

* **🐛 [Reporte um Problema](https://discord.gg/allianceoficial)**: Encontrou um bug? Me avise!
* **💬 [Faça uma sugestão](https://discord.gg/allianceoficial)**: Tem ideias ou sugestões? Eu adoraria lhe ouvir.
<br>


## Créditos




<div style="text-align:; font-weight: bold; margin-bottom: 10px;">
  ㅤKellerㅤ
</div>

<table>
  <tr>
    <td style="text-align: center; margin-right: 20px;">
      <a href="https://www.instagram.com/kellerffx">
        <img src="https://i.imgur.com/25Qrvbh.png" alt="kellerSS" style="width: 50px; height: 50px;">
      </a>
  </tr>
</table>






## 🎗 Licença

Copyright KellerSS © 2025-2030.<br />

<div align="left">
</div>

<img src="https://i.imgur.com/NnWf7Fm.png" alt="line break" width="100%" height="3px">
