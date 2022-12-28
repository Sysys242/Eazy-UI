<h2 align="center">Eazy-UI</h2>
<h3 align="center">Make your beautifull ui, simply</h3>
<br>

---
<br>
<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-0.1-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/Sysys242/Eazy-UI/blob/main/README.md" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/Sysys242/Eazy-UI" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
</p><br>

---

<h3 align="center">Installation</h3><br>

```
pip install eazy-ui
```

<h3 align="center">Ascii</h3><br>

```
from eazy_ui import *

Ascii.print("EazyUi", AsciiType.ALLIGATOR2) # print ascii
Ascii.get("EazyUi", AsciiType.ALLIGATOR2) # get ascii text
```
<img src="https://media.discordapp.net/attachments/1057393046855110716/1057618666591621130/image.png" width="40%">

<h3 align="center">Colors</h3><br>

_from pystyle_

```
from eazy_ui import *

print(Colors.red + "Hello")
```
<img src="https://media.discordapp.net/attachments/1057393046855110716/1057618959635066920/image.png" width="20%">

<h3 align="center">Center</h3><br>

_from pystyle_

```
from eazy_ui import *

print(Center.XCenter("Hello"))
```
<img src="https://media.discordapp.net/attachments/1057393046855110716/1057619416369594499/image.png" width="60%">

<h3 align="center">Console Output</h3><br>

```
from eazy_ui import *

Console.printSuccess("Hello", PrintType.FIRST)
```
<img src="https://media.discordapp.net/attachments/1057393046855110716/1057620369973968976/image.png" width="30%">

<h3 align="center">Refreshing Screen</h3><br>

```
from eazy_ui import *

refreshingScreen = RefreshingScreen(Ascii.get("EasyUI", AsciiType.ALLIGATOR2), "First", "Second", screenType=RefreshingScreenType.CENTERED)
refreshingScreen.start()

while True:
    time.sleep(1)
    refreshingScreen.updateValue(val2=int(refreshingScreen.val2)+1)
```
<img src="https://media.discordapp.net/attachments/1057393046855110716/1057621151486066698/image.png?width=1440&height=287" width="50%">