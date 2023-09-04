# awaken notification Ui Library

## ⚡ Features

- Clean Ui
- Ui modes for example: Error, Warn, Info
- Really simple to use
<br/>

## 🔌 Installation

You can load Fluent through a GitHub Release:

```lua
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Awakenchan/Awaken-UI-s/main/Notification%20Ui"))() 
local awakenNotification = library:CreateWindow()
```
<br/>

## 📜 Usage
```lua
test:CreateNotification(
    'Warn:',
    game.Players.LocalPlayer.Name,
    14404156927,
    4
)

test:CreateNotification(
    'Info:',
    game.Players.LocalPlayer.Name,
    14404156927,
    4
)

test:CreateNotification(
    'Error:',
    game.Players.LocalPlayer.Name,
    14404156927,
    4
)

test:CreateNotification(
    'AnyText:',
    'Example',
    14404156927,
    4
)

test:CreateNotification(
    Tittle,
    Content,
    AssetId,
    Waitvalue
)

```
<br/>

## Credits

- awakenkn / https://e-z.bio/awaken
