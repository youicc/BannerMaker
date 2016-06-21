# BannerMaker
[![Build Status](https://ci.kid7.club/job/BannerMaker/badge/icon)](https://ci.kid7.club/job/BannerMaker/)  
[![MCStats](http://i.mcstats.org/BannerMaker/Global+Statistics.png)](http://mcstats.org/plugin/BannerMaker)
## Link
* [BukkitDev](http://dev.bukkit.org/bukkit-plugins/bannermaker/)
* [Spigot Resource](http://www.spigotmc.org/resources/bannermaker.4380/)
* ~~[巴哈姆特](http://forum.gamer.com.tw/C.php?bsn=18673&snA=123519&tnum=1)~~（已自動消失）
* [巴哈小屋](http://home.gamer.com.tw/creationDetail.php?sn=2760067)
* [MCBBS](http://www.mcbbs.net/thread-415289-1-1.html)

## English / 英文

Feel banner is fun but you don't know how to craft?  
It's too hard to craft so you make wrong usually?  
You must try this plugin.

### Description
Using just one command, you can use GUI of this plugin to design any kind of banner.  
You don't need to know how to craft. All you need to know is how it will looks like.

### Features
* Design and save banner
* Look up recipe of banner
* Support UUID
* Multi language support (Setting in config.yml)  
  * English(en)
  * Traditional Chinese(zh-tw)
  * Simplified Chinese(zh-cn)
  * German(de) (Thanks [Marrarus](https://github.com/Marrarus))
  * French(fr) (Thanks [RedNesto](https://github.com/RedNesto))
* Economic support (need Vault)
* Material estimates

### How to use
* Look at pictures at bottom of page

### Commands
|**Command**|**Description**|
|---|---|
|/bm|Open main gui|
|/bm reload|Reload config|

### Permissions
|**Permission**|**Description**|
|---|---|
|BannerMaker.*|Whole permission|
|BannerMaker.use|Use /bm|
|BannerMaker.getBanner|Get banners from GUI|
|BannerMaker.getBanner.free|Get banners for free|
|BannerMaker.reload|Use /bm reload|

### Features in future
* Use craft materials to get banner
* Generate give command
* Generate summon command
* ...and tell me what you want

### Installation
1. Shutdown the server
2. Put the .jar into the plugins folder
3. Start the server

### Change Logs
v1.4.5 (for 1.8.x, 1.9.x)
- Fix "Title cannot be longer than 32 characters" exception

v1.4.4 (for 1.8.x, 1.9.x)
- Optimize code
- Prevent "Title cannot be longer than 32 characters" exception
- Add Plugin Metrics

v1.4.3 (for 1.8.x, 1.9.x)
- Add French(fr) translation (Thanks [RedNesto](https://github.com/RedNesto))
- Update recipe of bordered alphabet D and R
- Update checking of language files
- Check if materials enough and show in banner info

v1.4.2 (for 1.8.x, 1.9.x)
- Update recipe of bordered alphabet S
- Add German(de) Translation (Thanks [Marrarus](https://github.com/Marrarus))
- Optimize code

v1.4.1 (for 1.8.x, 1.9.x)
- Add menu of Alphabet & Number
- Add craft material estimates
- Make GUI title prefix editable
- Fix wrong wool color of black banner
- Optimize performance

v1.4 (for 1.8.x, 1.9.x)
- Update to 1.9.2
- Remove old preview mode (banner icons will never disappear)
- Make message prefix editable
- Add "Clone & Edit" button

v1.3.2 (for 1.8.x)
- Remove unnecessary debug messages
- Drop banner on the ground if get banner when inventory is full
- Tried to fix IndexOutOfBoundsException
- Create a toggle button preview mode in create-banner-menu

v1.3.1 (for 1.8)
- Fixed some bug

v1.3 (for 1.8)
- Add Economic support (need Vault)

v1.2 (for 1.8)
- Support UUID
- Multi language support  
(Setting in config.yml. Now support English(en),Traditional Chinese(zh-tw), Simplified Chinese(zh-cn))

v1.1 (for 1.8)
- Move banner data to folder "banner"
- More clear and smaller data format  
(Move all &lt;player&gt;.yml to folder "banner" and it will be auto update to new data format)

v1.0 (for 1.8)
- First Release


＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝

## Chinese / 中文

覺得旗幟很有趣，但又不知道該如何合成？  
合成公式太複雜，以致於常常出錯？  
你一定要試試這個這個插件

### 描述
只要一個指令，你將能透過這插件的介面，設計無數種旗幟。  
不需要瞭解旗幟合成方式，只要知道你希望旗幟長怎樣。

### 功能
* 設計並儲存旗幟
* 查詢旗幟合成表
* 支援UUID
* 多國語言（在config.yml設定）  
  * 英文(en)
  * 正體中文(zh-tw)
  * 簡體中文(zh-cn)
  * 德文(de)（感謝 [Marrarus](https://github.com/Marrarus)）
  * 法文(fr)（感謝 [RedNesto](https://github.com/RedNesto)）
* 支援經濟功能（需要Vault）
* 材料估算

### 使用方法
* 請見最下方圖片

### 指令
|**指令**|**描述**|
|---|---|
|/bm|開啟主要介面|
|/bm reload|重新載入設定檔|

### 權限
|**權限**|**描述**|
|---|---|
|BannerMaker.*|完整權限|
|BannerMaker.use|使用/bm|
|BannerMaker.getBanner|從介面取得旗幟|
|BannerMaker.getBanner.free|免費取得旗幟|
|BannerMaker.reload|使用/bm reload|

### 未來功能
* 使用合成材料來取得旗幟
* 產生give指令
* 產生summon指令
* ...告訴我你還想要什麼

### 安裝
1. 關閉伺服器
2. 將 .jar 放入 plugins 資料夾
3. 啟動伺服器

### 更新紀錄
v1.4.5 (for 1.8.x, 1.9.x)
- 修正「Title cannot be longer than 32 characters」例外

v1.4.4 (for 1.8.x, 1.9.x)
- 優化程式碼
- 防止「Title cannot be longer than 32 characters」例外
- 新增 Plugin Metrics

v1.4.3 (for 1.8.x, 1.9.x)
- 新增法文(fr)翻譯（感謝 [RedNesto](https://github.com/RedNesto)）
- 更新有框字母D和R的合成表
- 更新語系檔檢查機制
- 檢查材料是否足夠，並顯示於旗幟資訊頁面

v1.4.2 (for 1.8.x, 1.9.x)
- 更新有框字母S的合成表
- 新增德文(de)翻譯（感謝 [Marrarus](https://github.com/Marrarus)）
- 優化程式碼

v1.4.1 (for 1.8.x, 1.9.x)
- 新增字母與數字選單
- 新增合成材料估算
- 令GUI標題前綴可編輯
- 修正黑色旗幟的羊毛顏色錯誤
- 優化效能

v1.4 (for 1.8.x, 1.9.x)
- 升級至1.9.2
- 移除舊的預覽模式（旗幟圖標將不會再消失）
- 令訊息前綴可編輯
- 新增「複製並編輯」按鈕

v1.3.2 (for 1.8.x)
- 移除非必要之除錯訊息
- 若包包已滿，取得旗幟時，旗幟將會掉在地上
- 嘗試修復IndexOutOfBoundsException
- 在建立旗幟頁面新增切換預覽模式的按鈕

v1.3.1 (for 1.8)
- 修正一些錯誤

v1.3 (for 1.8)
- 新增支援經濟功能（需要Vault）

v1.2 (for 1.8)
- 支援UUID
- 多國語言  
（在config.yml設定，目前支援英文(en)、正體中文(zh-tw)、簡體中文(zh-cn)）

v1.1 (for 1.8)
- 旗幟資料移至「banner」資料夾
- 更清晰、更小的資料格式  
（將所有 &lt;玩家&gt;.yml 移至「banner」資料夾，它將會自動更新到新格式）

v1.0 (for 1.8)
- 第一次釋出

＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝＝
## Pictures / 圖片
![Main menu](http://i.imgur.com/rMTTfsE.png)  
![Create banner](http://i.imgur.com/HB6Dhm3.png)  
![Banner info](http://i.imgur.com/Xydmcbj.png)  
![Alphabet & Number](http://i.imgur.com/tGHmakp.png)
