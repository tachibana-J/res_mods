## WoWS mods that Destroyer_Tachibana maintains:

####*<p align="center">Read the [changelog](./CHANGELOG.md) today!</p>*

1. Japanese text mod `/texts`  (only `global.mo` is necessary) AND `fontconfig.xml` AND an SEA-client `fonts_all.swf` (or see item 6):
    
    &nbsp;&nbsp;A. HUD UI elements (pulled from SEA client text file) are in Japanese;
    
    &nbsp;&nbsp;B. Asian ship names are displayed in Japanese (kanji with exception of ARP ships);
    
    &nbsp;&nbsp;C. Asian captain names are changed to those of historical figures, displayed in Japanese (kanji);
    
    &nbsp;&nbsp;D. Reworded certain features, including:

    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. Achievements:
    <table style="margin: 0px auto; text-align: center;">
        <tr>
            <th>NA name</th>
            <th>SEA name</th>
            <th>This mod</th>
        </tr>
        <tr>
            <td>Detonation</td>
            <td>爆沈</td>
            <td>轟沈</td>
        </tr>
        <tr>
            <td>Dreadnought</td>
            <td>ドレッドノート</td>
            <td>弩級</td>
        </tr>
        <tr>
            <td>High Caliber</td>
            <td>大口径</td>
            <td>勇戦</td>
        </tr>
        <tr>
            <td>Devastating Strike</td>
            <td>破壊的一撃</td>
            <td>全門斉射</td>
        </tr>
        <tr>
            <td>It's Just a Flesh Wound!</td>
            <td>かすり傷さ!</td>
            <td>道連れ</td>
        </tr>
        <tr>
            <td>Confederate</td>
            <td>共謀者</td>
            <td>援護</td>
        </tr>
        <tr>
            <td>Kraken Unleashed!</td>
            <td>クラーケン来襲!</td>
            <td>無双</td>
        </tr>
        <tr>
            <td>Solo Warrior</td>
            <td>孤高の戦士</td>
            <td>一縷の希望</td>
        </tr>
        <tr>
            <td>Clear Sky</td>
            <td>晴天</td>
            <td>防空</td>
        </tr>
        <tr>
            <td>Close Quarters Expert</td>
            <td>接近戦エキスパート</td>
            <td>接近戦専門</td>
        </tr>
        <tr>
            <td>?</td>
            <td>?</td>
            <td>武士の情け</td>
        </tr>
        <tr>
            <td>?</td>
            <td>?</td>
            <td>見えざる脅威</td>
        </tr>
    </table>
    
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. Signal flags' texts
      
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. リザーブ → 営舎、エリア → 海域、ゾーン → 陣地、(etc.)
      
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. Certain unnatural expressions: 配属する: → 配属させる:
    
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e. Nation names are changed to mimic a WWII environment, displayed in Japanese (kanji);
      
    &nbsp;&nbsp;E. Modules of Asian ships, mostly IJN for now, are changed to be as historically accurate as technically allowed. 
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Exceptions:
    
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. 古鷹の後期主砲(tech.)
        
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. 陽炎の主砲(tech.)
        
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. 白龍の後期爆撃機「Wakusei」(hist. to-be-corrected)
        
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. 蔵王の主砲「Type 18」&魚雷「Type F3」(hist. creatively corrected);
      
    &nbsp;&nbsp;F. Easter egg(s?).
    

2. AP tracer color mod `/particles`: a simple recoloring of AP shell tracers to give a ice-blue for own shells and green for others' shells (friendly and hostile).

3. Flag mod `/content/gameplay/common/flags`: a shameless redo of a certain 2K flag mod, using historical navy flags of IJN and KM from Wikipedia.

4. Camouflage mod `/camouflages.xml` AND `/content/gameplay/common/camouflage`: a systematic recoloring of IJN "pickle-green" camos and others that I possess into more discreet versions. **(pic to-do)**

5. Dock mod `/spaces/Dock_ocean`: a simple tweak of the Ocean dock to allow better water/lighting/wind.

6. **WIP** Japanese font mod `/gui/flash/fonts_all.swf`: an in-place swf resource replacement allowing better alphanumeric display with the default Japanese font: by default the Source Hans Sans is partially replaced (basic latin and numeric characters) with WG's WarHelicC, but new characters like ō, ǒ, ł, etc. are missing or using the wider Source Hans Sans, resulting in an ugly interface. The fonts of these characters have now been replaced with WarHelicC (extracted from NA client), but spacing may be wrong, resulting in bugs.
