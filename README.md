![themes](https://github.com/user-attachments/assets/fb2821a0-d67d-4d29-bd11-14d6a5150ad0)
<p align="center">
  A theme for <a href="https://github.com/amnweb/yasb">YASB</a> using the most popular color schemes
  
### Usage
- Install [JetBrainsMono Nerd Font](https://www.nerdfonts.com/font-downloads)
- Download the repository to your computer
- Select the theme you need and copy it to `~\.config\yasb`
- Open the `config.yaml` file and change the `location` line in `weather` to your city and country.
```yaml
weather:
    type: "yasb.weather.WeatherWidget"
    options:
      ***
      location: 'Russia Moscow' # You can use "USA Los Angeles 90006", or just city.
      ***
```
- To make the list of applications work, you need to change the path to the applications in the `apps` line of `config.yaml`. You can also add any application you need there and modify it. Icons can be found at [Nerd Fonts Cheat Sheet](https://www.nerdfonts.com/cheat-sheet)
```yaml
  apps:
    type: "yasb.applications.ApplicationsWidget"
    options:
      ***
      app_list:
        - {icon: "\uf4d4", launch: "explorer"} 
        - {icon: "\uf282", launch: "C:\\Program Files (x86)\\Microsoft\\Edge\\Application\\msedge.exe"}
        - {icon: "\uf023", launch: "C:\\Program Files\\AmneziaVPN\\AmneziaVPN.exe"}
        - {icon: "\ue217", launch: "C:\\Users\\user\\AppData\\Roaming\\Telegram Desktop\\Telegram.exe"}
        - {icon: "\uf1ff", launch: "C:\\Users\\user\\AppData\\Local\\Discord\\Update.exe --processStart Discord.exe"}
      ***     
```
- To use the light theme, you need to enable light mode in Windows
***

<details>
<summary><b>Catpuccin</b></summary>

**`Macha`**
![catpuccin-mocha](https://github.com/user-attachments/assets/53df9c5c-b682-4205-8eea-d02baa50a650)

**`Macchiato`**
![catpuccin-macchiato](https://github.com/user-attachments/assets/238a59e1-d0a3-4658-b246-d306bd680637)

**`Frape`**
![catpuccin-frappe](https://github.com/user-attachments/assets/f9cb42fe-bd1e-4eae-9049-1f4c3fafa943)

**`Latte`**
![catpuccin-latte](https://github.com/user-attachments/assets/921f8e99-4376-46f5-9b29-6785eba490b7)

</details>

<details>
<summary><b>Everforest</b></summary>

**`Hard`**
![everforest-hard](https://github.com/user-attachments/assets/41394f1c-c43f-42d4-b981-02a5caf6a020)
![everforest-hard-light](https://github.com/user-attachments/assets/5f70c993-f356-456c-aa5f-079db56c1af6)

**`Medium`**
![everforest-medium](https://github.com/user-attachments/assets/72071908-8ca9-4630-ad26-dd7e46ac7054)
![everforest-medium-light](https://github.com/user-attachments/assets/0da01ac6-5168-4660-9330-cfca00697b80)

**`Soft`**
![everforest-soft](https://github.com/user-attachments/assets/d88f8492-9a93-4a58-88df-98becc5752d9)
![everforest-soft-light](https://github.com/user-attachments/assets/ae370e06-553d-4c18-bab4-ce4f97be8ce6)

</details>

<details>
<summary><b>Gruvbox</b></summary>

**`Dark`**
![gruvbox-dark](https://github.com/user-attachments/assets/fed8569b-8077-4c12-beee-c4c17a38c7bf)

**`Light`**
![gruvbox-light](https://github.com/user-attachments/assets/653f475f-b12f-4e37-a733-e96d5d36feee)

</details>

<details>
<summary><b>Rose-pine</b></summary>

**`Main`**
![rose-pine](https://github.com/user-attachments/assets/e58433a9-409f-4599-b641-d6912120ca30)

**`Moon`**
![rose-pine-moon](https://github.com/user-attachments/assets/fb275988-3870-48d5-b4c8-ed4823a60ec1)

**`Dawn`**
![rose-pine-dawn](https://github.com/user-attachments/assets/506cf5e8-fa09-4197-b3e3-f956da126bb5)

</details>

<details>
<summary><b>Tokyonight</b></summary>

**`Night`**
![tokynight-night](https://github.com/user-attachments/assets/9a4dfaad-60ed-4dfa-83c3-e342a9f6afbe)

**`Storm`**
![tokyonight-storm](https://github.com/user-attachments/assets/17285f4c-bb96-4c4d-ad99-58c124345027)

**`Light`**
![tokyonight-light](https://github.com/user-attachments/assets/55b9d7f9-6789-488b-993e-68b0f4d7a143)

</details>
