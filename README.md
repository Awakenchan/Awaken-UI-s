# awaken notification Ui Library

## ⚡ Features

- Clean Ui
- Ui modes for example: Error, Warn, Info
- Really simple to use
<br/>

## 🔌 Installation

You can load awaken notification through a GitHub Release:

```lua
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Awakenchan/Awaken-UI-s/main/Notification%20Ui"))() 
local awakenNotification = library:CreateWindow()
```
<br/>

## 📜 Usage
```lua
awakenNotification:CreateNotification(
    'Warn:',
    game.Players.LocalPlayer.Name,
    14404156927,
    4
)

awakenNotification:CreateNotification(
    'Info:',
    game.Players.LocalPlayer.Name,
    14404156927,
    4
)

awakenNotification:CreateNotification(
    'Error:',
    game.Players.LocalPlayer.Name,
    14404156927,
    4
)

awakenNotification:CreateNotification(
    'AnyText:',
    'Example',
    14404156927,
    4
)

awakenNotification:CreateNotification(
    Tittle,
    Content,
    AssetId,
    Waitvalue
)

```
<br/>

## Credits

- awakenkn / https://e-z.bio/awaken
