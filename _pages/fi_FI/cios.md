---
title: "cIOS"
---

{% include toc title="Table of Contents" %}

Tämä opas kertoo sinulle, kuinka asentaa cIOS (custom IOS). Tämä vaaditaan, jos haluat käynnistää pelejä USB-lataajan kautta. Jotkut homebrew-ohjelmat saattavat toimia paremmin cIOS:ia käyttämällä.

![d2x cIOS Installer](/images/cios/cIOS.png)

Jos sinulla on Wii mini, asenna [tämä cIOS](cios-mini). Muun cIOS:n asentaminen Wii minille ei tule toimimaan.
{: .notice--info}

#### Mitä tarvitset

* Wii internetyhteydellä
* An SD card or USB drive
* [d2x cIOS Installer](/assets/files/d2x-cIOS-Installer-Wii.zip)

Ensure that if you are using an SD card, the lock switch is in the unlocked position, otherwise you will not be able to select the correct options in the installer
{: .notice--warning}

#### Ohjeet

##### Osa I - Lataaminen

1. Lataa d2x cIOS Installer ja pura se `apps` kansioon SD-kortillesi tai USB-asemallesi.
1. Liitä SD-korttisi tai USB-asemasi Wii-konsoliisi ja käynnistä d2x cIOS Installer Homebrew Channelista.

##### Osa II - Asentaminen

1. Paina continue, sitten aseta vaihtoehdot seuraavasti:
```
Select cIOS: v10 beta52 d2x-v10-beta52
Select cIOS base: 57
Select cIOS slot: 249
Select cIOS version: 65535
```
![Install cIOS 249](/images/cios/Install249.png)
1. Kun asetettu, paina A:ta kahdesti asentaaksesi.
1. Kun asennus on valmis, paina A:ta palataksesi ja aseta vaihtoehdot seuraavasti:
```
Select cIOS: v10 beta52 d2x-v10-beta52
Select cIOS base: 56
Select cIOS slot: 250
Select cIOS version: 65535
```
![Install cIOS 250](/images/cios/Install250.png)
1. Kun asetettu, paina A:ta kahdesti asentaaksesi.
1. When done installing, press A to return, and set the options to the following: ![Install cIOS 251](/images/cios/Install251.png)
```
Select cIOS: v10 beta52 d2x-v10-beta52
Select cIOS base: 38
Select cIOS slot: 251
Select cIOS version: 65535
```
1. Kun asetettu, paina A:ta kahdesti asentaaksesi ja sen jälkeen poistu, kun valmista.

Although the majority of games should work straight away, some may require using a specific cIOS to function, or to utilize certain features within the game. To change the cIOS used for a specific game, follow these instructions:
{: .notice--warning}

<button class="tablinks btn btn--large btn--primary" id="defaultOpen" onclick="openTab(event, 'usbloadergx')">USB Loader GX</button>
<button class="tablinks btn btn--large btn--info" onclick="openTab(event, 'wiiflow')">WiiFlow</button>

<div id="usbloadergx" class="blanktabcontent">
  <p spaces-before="0">
    !!crwdP_23_Pdwrc!!Select the game that isn't working. !!crwdP_24_Pdwrc!!Click Settings. !!crwdP_25_Pdwrc!!Select <code>Game Load</code>. !!crwdP_26_Pdwrc!!Scroll down to <code>Game IOS</code>. !!crwdP_27_Pdwrc!!Enter the IOS slot to use.
  </p>
  
  <ul>
    <li>
      Try using 250 or 251, if 249 doesn't work. !!crwdP_28_Pdwrc!!Press ok and try to load the game
    </li>
  </ul>
</div>

<div id="wiiflow" class="blanktabcontent">
  <p spaces-before="0">
    !!crwdP_29_Pdwrc!!Select the game that isn't working. !!crwdP_30_Pdwrc!!Click the gear icon. !!crwdP_31_Pdwrc!!Go to cIOS and use the arrows to select the IOS slot to use.
  </p>
  
  <ul>
    <li>
      Try using 250 or 251, if 249 doesn't work. !!crwdP_32_Pdwrc!!Press Save and try to load the game.
    </li>
  </ul>
</div>
##### Vaihtoehdot, kun valmista

[Continue to the Homebrew Browser](hbb)<br> The Homebrew Browser is a good place to get homebrew on your Wii. This is optional to install.
{: .notice--info}

[Continue to site navigation](site-navigation)<br> We have many other tutorials that you might like.
{: .notice--info}

Voit nyt käyttää homebrew-sovelluksia, kuten [USB Loader GX:ää](usbloadergx) ja [WiiFlowia](wiiflow).
{: .notice--info}

<script>
    let tabcontent = document.getElementsByClassName("blanktabcontent");
    let tablinks = document.getElementsByClassName("tablinks");!!crwd_CB_10_BC_dwrc!!</script>

