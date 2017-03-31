## WoWS mods that Destroyer_Tachibana maintains:

####*<p align="center">Read the [changelog](./CHANGELOG.md) today!</p>*

1. Japanese text mod `/texts`  (only `global.mo` is necessary) AND `locale_config.xml` (or see item 5):
    
    &nbsp;&nbsp;A. HUD UI elements (pulled from SEA client text file) are in Japanese;
    
    &nbsp;&nbsp;B. Asian ship names are displayed in Japanese;
    
    &nbsp;&nbsp;C. Asian captain names are changed to those of historical figures, displayed in Japanese;
    
    &nbsp;&nbsp;D. Reworded certain features, including:

    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. Achievements:
    
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. Signal flags texts
      
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. リザーブ → 営舎、エリア → 海域、ゾーン → 陣地、(etc.)
      
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d. Certain unnatural expressions: 配属する: → 配属させる:
    
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e. Nation names are changed to mimic a WWII environment, displayed in Japanese (kanji);
      
    &nbsp;&nbsp;E. Modules of Asian ships, mostly IJN for now, are changed to be as historically accurate as technically allowed. 
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Exceptions:
        
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. 白龍の後期爆撃機「Wakusei」(hist. creatively corrected)
        
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. 蔵王の主砲「Type 18」(hist. creatively corrected)
    
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. 魚雷「Type F3」(hist. creatively corrected);
      
    &nbsp;&nbsp;F. Easter eggs.
    

2. AP tracer color mod `/particles`: a simple recoloring of AP shell tracers to give an ice-blue color for own fort shells and green for all others' shells (friendly and hostile).

3. Flag mod `/content/gameplay/common/flags`: an innovative approach to easing the update of this mod by altering the `atlas` coordination file to read a remote region of the dds file that is currently blank.

4. Camouflage mod `/camouflages.xml`: a systematic recoloring of IJN "pickle-green" camos and some others that I possess into more discreet versions.

5. Japanese font mod `/gui/flash/fonts_ASIA.swf` AND `fontconfig.xml`: a remake of the flash file that contains fonts used by the game. The flash file has a very barebone layout — two texts of "regular" and "bold" font-face on a 550x400@25fps canvas, with those two (or more, a total of four used by the game) actual fonts' files embeded, and anti-aliasing settings to "custom" with sharpness and thickness both at 0. Export to swf with Flash ver. 10.3. Extract the packed fontconfig.xml (*do not use the loose one in `/res`*), and change the fonts' names to yours'.
