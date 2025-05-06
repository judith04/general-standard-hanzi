# general-standard-hanzi
Files related to 《通用规范汉字表》 (*Table of General Standard Chinese Characters*).

<br>

## File list

<br>

- `\通用规范汉字表\`
  - `通用规范汉字表.pdf`: scanned original document released by China's Ministry of Education.
  - `通用规范汉字表.xlsx`: Excel worksheet containing all characaters of 《通用规范汉字表》, along with their Unicode code points, PUA/wrong code points in `\方正规范书宋\FZGFShuSong.TTF` (if exist) and Mandarin readings.

<br>

- `\方正规范书宋\`
  - `FZGFShuSong.TTF`: **(unrecommended)** FounderType's original version of 方正规范书宋 (FZGFShuSong), containing all characters of 《通用规范汉字表》, although some are only mapped to PUA or wrong code points. It will be automatically installed by 方正通用规范字库（个人版）.
  - `FZGFShuSong_comp.ttf`: **(unrecommended)** modified version of 方正规范书宋, compatible with both GBK and Unicode. The version also inherits all wrong code points of `FZGFShuSong.TTF` in order to keep compatible with 方正典码输入法（规范字表版）, so only use it if you have to.
  - `FZGFShuSong_uni.ttf`: **(recommended)** modified version of 方正规范书宋, fully compliant with Unicode.

<br>

- `\方正通用规范字库（个人版）\`
  - `setup.rar`: containing the installer of 方正通用规范字库（个人版） and 《通用规范汉字总表》.

<br>

## Appendix

<br>

Listed below are some characters that might be mapped to non-standard code points in `FZGFShuSong.TTF` and `FZGFShuSong_comp.ttf`. Remember that you should never use those *italic* code points unless you have to.

<br>

### PUA characters inherited from 《汉字内码扩展规范（GBK）》 (*Chinese Internal Code Specification*)

<br>

|     |    *unsuffixed*     |        _comp        |   _uni   |
| :-: | :-----------------: | :-----------------: | :------: |
|  㑇  |      `U+3447`       | `U+3447` *`U+E81B`* | `U+3447` |
|  㘎  |      `U+360E`       | `U+360E` *`U+E821`* | `U+360E` |
|  㤘  | `U+3918` *`U+E825`* | `U+3918` *`U+E825`* | `U+3918` |
|  㧐  | `U+39D0` *`U+E82A`* | `U+39D0` *`U+E82A`* | `U+39D0` |
|  㧟  | `U+39DF` *`U+E828`* | `U+39DF` *`U+E828`* | `U+39DF` |
|  㭎  |      `U+3B4E`       | `U+3B4E` *`U+E82D`* | `U+3B4E` |
|  䁖  | `U+4056` *`U+E834`* | `U+4056` *`U+E834`* | `U+4056` |
|  䅟  |      `U+415F`       | `U+415F` *`U+E835`* | `U+415F` |
|  䏝  | `U+43DD` *`U+E83F`* | `U+43DD` *`U+E83F`* | `U+43DD` |
|  䓖  |      `U+44D6`       | `U+44D6` *`U+E840`* | `U+44D6` |
|  䜣  |      `U+4723`       | `U+4723` *`U+E844`* | `U+4723` |
|  䥽  | `U+497D` *`U+E84B`* | `U+497D` *`U+E84B`* | `U+497D` |
|  䦃  | `U+4983` *`U+E84D`* | `U+4983` *`U+E84D`* | `U+4983` |
|  䲟  |      `U+4C9F`       | `U+4C9F` *`U+E857`* | `U+4C9F` |
|  䲠  |      `U+4CA0`       | `U+4CA0` *`U+E858`* | `U+4CA0` |
|  䲢  |      `U+4CA2`       | `U+4CA2` *`U+E85B`* | `U+4CA2` |
|  䴓  |      `U+4D13`       | `U+4D13` *`U+E85C`* | `U+4D13` |
|  䴔  |      `U+4D14`       | `U+4D14` *`U+E85D`* | `U+4D14` |
|  䴕  |      `U+4D15`       | `U+4D15` *`U+E85E`* | `U+4D15` |
|  䴖  |      `U+4D16`       | `U+4D16` *`U+E85F`* | `U+4D16` |
|  䴗  |      `U+4D17`       | `U+4D17` *`U+E860`* | `U+4D17` |
|  䴘  |      `U+4D18`       | `U+4D18` *`U+E861`* | `U+4D18` |
|  䴙  |      `U+4D19`       | `U+4D19` *`U+E862`* | `U+4D19` |
|  䶮  |      `U+4DAE`       | `U+4DAE` *`U+E863`* | `U+4DAE` |

<br>

### PUA characters inherited from 方正宋体-人口信息 (FZSong-RKXX)

<br>

|     | *unsuffixed* |        _comp        |   _uni   |
| :-: | :----------: | :-----------------: | :------: |
|  鿍  |  *`U+E295`*  | `U+9FCD` *`U+E295`* | `U+9FCD` |
|  鿎  |  *`U+E37E`*  | `U+9FCE` *`U+E37E`* | `U+9FCE` |
|  鿏  |  *`U+F344`*  | `U+9FCF` *`U+F344`* | `U+9FCF` |

<br>

### Wrongly-mapped characters

<br>

|     | *unsuffixed* |         _comp         |   _uni    |
| :-: | :----------: | :-------------------: | :--------:|
|  𫢸  | *`U+2B8B9`*  | `U+2B8B8` *`U+2B8B9`* | `U+2B8B8` |
|  𫫇  | *`U+2BAC8`*  | `U+2BAC7` *`U+2BAC8`* | `U+2BAC7` |
|  𫭟  | *`U+2BB60`*  | `U+2BB5F` *`U+2BB60`* | `U+2BB5F` |
|  𫭢  | *`U+2BB63`*  | `U+2BB62` *`U+2BB63`* | `U+2BB62` |
|  𫭼  | *`U+2BB7D`*  | `U+2BB7C` *`U+2BB7D`* | `U+2BB7C` |
|  𫮃  | *`U+2BB84`*  | `U+2BB83` *`U+2BB84`* | `U+2BB83` |
|  𫰛  | *`U+2BC1C`*  | `U+2BC1B` *`U+2BC1C`* | `U+2BC1B` |
