[TFT_2.2-inch](https://github.com/KitSprout/TFT_2.2-inch)
========
* Author  : [Hom](http://about.me/Hom)
* Version : v1.2
* Update  : 2015/02/25

Description
========
TFT_2.2-inch 是一個 2.2 吋的 TFT LCD 模組，透過 SPI 傳輸資料，上面另外帶有 SD 卡座，共用相同的 SPI。

*** 尚未測試 SD 卡，其他都可正常運作。

License
========
* 硬體(Hardware)採用 [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW) 方式授權 
  
　　<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW"><img alt="創用 CC 授權條款" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/tw/80x15.png" /></a>  
　　<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title"> TFT_2.2-inch v1.2 </span>由<a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/KitSprout" property="cc:attributionName" rel="cc:attributionURL"> KitSprout </a>製作，以<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW"> 創用CC 姓名標示-相同方式分享 4.0 國際 授權條款 </a>釋出。  

Hardware
========
* 控制器 : [ILI9341](http://www.ilitek.com/index.asp)
* 解析度 : 320*240
* 其他外接 : SD ( SPI )
* PCB 尺寸 : 67.82 * 40.89mm
* 設計軟體 [Altium Designer 14](http://www.altium.com/en/products/altium-designer) ( PcbLib use AD [PcbLib v1.0](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases/tag/v1.0) ) 

Source Code
========
[STM32 - MungBeanSprout](https://github.com/KitSprout/MungBeanSprout/tree/master/Software/BSM_TestTFT2.2)  
[STM32 - RedBeanSprout](https://github.com/KitSprout/RedBeanSprout/tree/master/Software/BSR_TestTFT2.2)  
[STM32 - QCopterFlightControl](https://github.com/QCopter/QCopterFlightControl/tree/Pre-v2.2/Software/TEST_QCopterFC_FFCSPI_TFT22)  
[STM32 - QCopterRemoteControl](https://github.com/QCopter/QCopterRemoteControl/tree/master/Software/TEST_QCopterRC_FFCSPI-TFT2.2)  

Related Documents
========
* [Google Drive](http://goo.gl/J0ovlt)

View
========
<img src="https://lh5.googleusercontent.com/-3nzlZW-4MJ8/U_CiPzzd5MI/AAAAAAAAKiA/tIfi7e3SYCI/s800/DSC_2466.jpg" />
<img src="https://lh4.googleusercontent.com/-xUzBCUzwRlA/U_CiOwgkCPI/AAAAAAAAKhg/tcrF7QWQI4s/s800/DSC_2455.jpg" />
<img src="https://lh6.googleusercontent.com/-QUGGIQQD6Pk/U_CiPPtBd4I/AAAAAAAAKiU/2F-gbQR-T_w/s800/DSC_2449.jpg" />
<img src="https://lh6.googleusercontent.com/-GndqyzcPHuQ/U_CiOnYjg9I/AAAAAAAAKiI/Upfku3Nb418/s800/DSC_2454.jpg" />

Schematic
========
<img src="https://lh6.googleusercontent.com/-wd8W0QbFmVk/U_Cld9vW1oI/AAAAAAAAKlc/9Wgle1PK5iU/s1200/Sch_TFT_2.2-inch_ILI9341.png" />