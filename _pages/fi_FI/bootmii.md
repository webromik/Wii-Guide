---
title: "BootMii Backup"
---

{% include toc title="Table of Contents" %}

Jos tarvitset apua missä tahansa tähän oppaaseen liittyvässä, liity [RiiConnect24:n Discord-palvelimelle](https://discord.gg/b4Y7jfD) (suositeltavaa) tai [ lähetä meille sähköpostia osoitteeseen support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![BootMii Logo](/images/bootmii.png)

Tarvitset **SD-kortin** luodaksesi NAND-varmuuskopion BootMiin avulla. Jos sinulla ei ole sellaista, voit ohittaa tämän sivun, vaikka onkin erittäin suositeltavaa luoda varmuuskopio, jos pystyt.
{: .notice--warning}

Yksi BootMiin tärkeimmistä ominaisuuksista on kyky varmuuskopioida ja palauttaa Wiisi NAND-tallennustila. We will be going over how to perform a NAND backup. You can then restore from that backup for whatever reason. We recommend making a NAND backup regularly or before you do something risky to your console (and if you know what you're doing, you won't have to do anything risky).

#### Vaatimukset
* SD-kortti, jolla on vähintään 512mt vapaata tilaa

#### Ohjeet
Jos asensit BootMiin boot2:een edellisessä vaiheessa, sinun täytyy käynnistää BootMii käynnistämällä konsoli uudelleen. Tässä tapauksessa ohita vaiheet 1-2.
{: .notice--info}
1. Käynnistä Homebrew Channel.
2. Paina HOME-nappia, sitten valitse "Launch BootMii".
   - BootMiissa ei voi navigoida Wii remotea käyttämällä. Sinun täytyy käyttää konsolin POWER- ja RESET-nappeja, tai porttiin 1 liitettyä GameCube-ohjainta. Navigoidaksesi asetusten välillä, paina Wiisi POWER-nappia (tai GameCube-ohjaimen ristiohjainta oikealle). Valitaksesi vaihtoehdon, paina Wiisi RESET-nappia tai GameCube-ohjaimen A-nappia.
3. Select the Options button (the one with the gears).
4. Valitse BackupMii-nappi (vihreän nuolen kuvalla).
- NAND-varmuuskopiointi alkaa. Voit seurata edistymistä näytöltä.
- "Bad Blockit" ovat tavallisia. Älä huoli nähdessäsi sellaisen NAND-varmuuskopiossa
- Tämän vaiheen jälkeen se tarkistaa varmuuskopion. Vaikka se on suositeltavaa, sen voi ohittaa painamalla Wiin EJECT-nappia.
5. Kun varmuuskopio on täysin valmis, poistu NAND-varmuuskopionäytöltä painamalla mitä tahansa nappia.
6. To exit BootMii, press the Back button (the one with the arrow) and then you can press either the Wii Menu button or the Homebrew Channel button to exit where you want to.

To restore from a NAND backup on your SD card, you can follow these instructions using RestoreMii (the button right next to BackupMii with a red arrow).
{: .notice--info}

[Continue to Priiloader Installation](priiloader) Priiloader adds a level of brick protection, and we recommend it, especially if you were only able to install BootMii IOS.
{: .notice--info}
