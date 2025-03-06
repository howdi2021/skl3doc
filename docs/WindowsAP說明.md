# Window AP 應用程式 
## 操作流程圖

<center><img src = "images/flowchart.png" width="150" height="auto"></img></center>

## 校正系統時間
**<div style="background: #e6f7ff; padding: 10px; border-radius: 5px; border: 1px solid #91d5ff;">因設定時間是以系統時間來計算，避免系統時間不準確，導致放飛設定時間與實際時間有誤差，所以必須校正系統時間。</div>**
1. 開啟標準時間網站：https://tw.piliapp.com/time-now/tw/taipei/ 或 https://time.is
2. 與系統時間比對是否同步?不同步則必須校正時間

	![](images/校正時間-1.png)

3. 校正時間步驟如下：
	- 開啟系統設定，選擇時間與語言選項
	
	![](images/校正時間-2.png)

	- 先關閉自動設定時間，之後手動設定日期與時間，將時間隨便調整，之後按立即同步，再把自動設定時間開啟。

	![](images/校正時間-3.gif)
	
	- 與系統時間比對是否同步?如同步則完成校正時間，不同步則重複上述步驟，直到時間同步。

	![](images/校正時間-4.png)

## 下載程式
1. 請至我的活動中，點擊Pro進入下載軟體程序。
	- 目前最新版 Windows AP 尚未放上網站 ，暫時在[這裡](https://minxin-my.sharepoint.com/:u:/g/personal/howdi_minxincorp_com/EZhubSv6AOVIuDgYjBW_nYgB3KiUM-xQa44SgvzSmXY_SQ?e=xtRmcy&download=1)下載

**<div style="background: #e6f7ff; padding: 10px; border-radius: 5px; border: 1px solid #91d5ff;">:star:在使用軟體之前，請確認是否已新增活動。<br> :star:<font color = #ff0000>設定腳環前，需先下載應用程式。</font> </div>**

![](images/16.png)

4. 點擊完Pro後，請至<font color = #ff0000>「下載」</font>尋找skyleader3壓縮檔，完成skyleader3資料夾解壓縮。

	![](images/22.png)

5. 完成解壓縮後，點進skyleader3資料夾裡。

	![](images/21.png)

6. 滑鼠左鍵快速點擊兩次:bird:skyleader3的應用程式，開啟使用者介面。

	![](images/23.png)


7. 登入畫面如圖所示，請輸入您的 <font color = #ff0000>ACCOUNT:帳號</font>及 <font color = #ff0000>PASSWORD:密碼</font>，登入帳密與 skyleader3 網頁相同。

	<img src = "images/ab.png" width="500" height="auto">


## 變更語言
1. 進入畫面後您會看到介面預設語言為您的系統預設語言，如無須調整請直接跳到:point_right:[設定放飛](#設定放飛)的操作說明。

	<img src = "images/ac.png" width="500" height="auto">

2. 請將滑鼠移動到程式<font color = #ff0000>左上方的Skyleader</font>字樣上，點擊後會跳出一個選單，點選<font color = #ff0000>Language:語言</font>，再點選選單內的<font color = #ff0000>Tradition Chinese:繁體中文</font>。

	<img src = "images/ad.png" width="500" height="auto">

3. 點選完成後會跳出一個小視窗，如下圖所示。
	- 點選小視窗上的OK按鍵，並重開程式即可完成語言的變更。
	
	<img src = "images/ae.png" width="500" height="auto">

4. 下圖為變化語言後的介面。

	![](images/af.png)

## 設定放飛

- 接下來將使用繁體中文介面做設定放飛的步驟說明。
- Mode C 3352腳環的設定時間參數，目前只能使用 periodic.json 來設定參數，詳細參考 [Mode C 紀錄模式設定](#Mode C 紀錄模式設定)

### Mode C 紀錄模式設定
- 因目前 skyleaer3.0 網站和Windows AP還不支援直接設定 Mode C 腳環紀錄模式，需要使用 periodic.json 來設定參數

-  periodic.json 需要放在 skyleader3 資料夾下，與skyleader3程式檔同一個資料夾。

	![](images/AP_peridoic-1.jpg)

- Windows AP只會讀取periodic.json裡面第一筆參數資料，如需要改其他參數，需要將參數移至第一筆

- 如有放置periodic.json，Windows AP會忽略 Web 網站上創活動時的紀錄模式

	![](images/AP_peridoic-2.jpg)

### 開始設定  

**<div style="background: #e6f7ff; padding: 10px; border-radius: 5px; border: 1px solid #91d5ff;">:star:在使用軟體之前，請確認是否已新增活動。<br> :star:<font color = #ff0000>設定腳環前，需先下載應用程式。</font> </div>**

1. 進入介面後點擊<font color = #ff0000>最左邊的圖示</font><img src = images/70.png width="40" height="auto">，並確認紅色按鈕的文字是否顯示<font color = #ff0000>「設定放飛」</font>，確認無誤即可進行下一步。

	![](images/ag.png)

2. 請檢查您的傳輸座否有正常運作。

	![](images/am.png)

3. 開始設定放飛時，請先點擊日期欄位旁的<font color =  #ff0000>按鍵(1)</font>，點選您在網頁上設定放飛的<font color = #ff0000>日期(2)</font>，最後在點擊<font color = #ff0000>「查看(3)」</font>，完成日期的選擇。

	![](images/ah.png)
	
4. 如果<font color = #ff0000>「查看」</font>沒有設定放飛的日期，會如下圖所示的畫面，跳出一個提示視窗，告訴您該日無放飛設定。

	![](images/aj.png)

5. 下圖為讀取到活動後會呈現的畫面，請您檢查<font color = #ff0000>活動、時間及模式</font>是否正確。

	![](images/ak.png)

6. 假設當天有超過一場活動，可點擊活動旁的按鈕，然後選擇要設定的活動。

	![](images/al.png)

7. 將腳環設置於傳輸座後點擊畫面右邊的<font color = #ff0000>「設定放飛」</font>按鈕，點擊後按鈕顏色會呈現灰色，代表點擊成功並開始寫入設定。

	![](images/an1.png)
8. 傳輸座欄位右邊會顯示腳環ID及設定的狀態。
	- :star:當出現<font color = #ff0000>Success(成功)</font>代表成功設定。
	- :star:當出現<font color = #ff0000>Fail(失敗)</font>代表設定失敗，請重新將腳環放置傳輸座。
	
	![](images/an2.png)
9. 完成設定後您可以回到👉 [skyleader3.0網頁](https://sport.skyleader.com.tw/Home/login)上，查看設定的腳環。

	![](images/by.png)


## 匯入會員資料

**<div style="background: #e6f7ff; padding: 10px; border-radius: 5px; border: 1px solid #91d5ff;">:star: 若您要用電子環掃描的方式綁定腳環，綁定前要先匯入會員資料，請您前往您所要綁定腳環的活動頁面中。 </div>**

![](images/66.png)

1. 請點擊<font color = #ff0000>匯入會員資料</font>。

	![](images/55.png)

2. 請先下載<font color = #ff0000>樣板</font>，打開樣板填寫資料。

	![](images/56.png)

3. 打開檔案後，您會看到以下的格式，請依照下方的說明填入資料。

	![](images/bl.png)

4. 選擇檔案，點擊剛填好的樣板檔案。

	![](images/57.png)

5. 點選下一步。

	![](images/58.png)

6. 您會看見剛剛匯入的資料。

	![](images/bm.png)

7. 確認資料無誤後，點擊<font color = #ff0000>匯入會員資料</font>，會在上方跳出小視窗詢問是否要匯入，點擊確定完成匯入。

	![](images/bn.png)

8. 進入步驟三後您可以看到匯入資料的狀況，點擊<font color = #ff0000>匯入完成</font>，完成匯入會員資料的所有程序。

	![](images/bo.png)




## 綁定GPS腳環

**<div style="background: #e6f7ff; padding: 10px; border-radius: 5px; border: 1px solid #91d5ff;">:star: 在綁定前請先關閉應用程式，並連接上您的Rfid感應器，完成後再開啟程式以便程式偵測到您的感應器。<br> :star:<font color = #ff0000>請不要在ComPort上連接Rfid感應器以外的裝置，有可能會偵測不到Rfid感應器。</font> </div>**

1. 請於<font color = #ff0000>設定放飛</font>的畫面上，將滑鼠移動到程式<font color = #ff0000>左上方的Skyleader</font>字樣上，點擊後會跳出一個選單，點選<font color = #ff0000>Rfid</font>，會跳出電子環感應器的設定介面。

	![](images/ao.png)

2. 點選<font color = #ff0000>Mode(模式)</font>欄位，您可選擇對應自己感應器的廠牌。
	- ToPigeon: 鴿神
	- AnJie: 安捷
	
	![](images/ap.png)

3. 完成Mode點選後，可點選<font color = #ff0000>Segment(長度)</font>，調整成您的電子環ID比對區段。

	![](images/aq.png)

4. 點擊<font color = #ff0000>Rfid</font>旁的![](images/at.png)按鈕，可調整要截取的號碼間段。

	![](images/ar.png)

5. 假設我的電子環ID長度要8，但號碼為AB23334441，我只需要數字的比對區段，就要設定於3-10之間。
6. 點擊![](images/at.png)按鈕後的示意圖

	![](images/as.png)

7. 完成Rfid設定後，點擊<font color = #ff0000>中間的鴿子圖示</font><img src = images/69.png width="40" height="auto"></img>，進入綁定功能的介面。

	![](images/au.png)

9. 綁定介面的示意圖

	<img src = "images/av.png" width="500" height="auto">

10. 在<font color = #ff0000>綁定</font>介面中是無法調整Rfid設定的，如需調整請再回到<font color = #ff0000>設定放飛</font>的介面調整。

	![](images/aw.png)


11. 請先載入要綁定的活動，然後即可點開綁定按鈕右邊的<font color = #ff0000>RFID Reader</font>。

	<img src = "images/ax.png" width="500" height="auto">

12. 點開後可以查看Reader欄位中的號碼是否與您的感應器相同，確認無誤後請點擊<font color = #ff0000>Binding Table</font>回到原先的畫面。

	<img src = "images/ay.png" width="500" height="auto">

14. 滑鼠點擊<font color = #ff0000>公環</font>旁的白色欄位，開始掃描電子環。

	<img src = "images/az.png" width="500" height="auto">

16. 掃描完下方的<font color = #ff0000>GPS ID</font>旁的白色欄位會開啟，緊接著掃描GPS腳環上的QRcode或手動輸入。
	- 掃描完QRcode系統會自動匯入綁定資料。
	- 手動輸入需在點擊下方的紅色<font color = #ff0000>綁定</font>按鈕或點擊鍵盤上的Enter鍵，完成一次綁定。

	<img src = "images/ba.png" width="500" height="auto">

17. 介面右方的<font color = #ff0000>Binding Table</font>表格中，會顯示您綁定的資料、筆數及時間，您可以透過這個表格確認資料是否正確。

	![](images/bb.png)

18. 如果有綁定錯誤的狀況，可以在<font color = #ff0000>公環</font>欄位上輸入要解除綁定的ID，在按下Enter鍵後會跳出一個小視窗詢問您，是否要重新綁定，點擊yes即可重新綁定。

	![](images/bc.png)

19. 也可以透過先輸入公環號再點擊下方的<font color = #ff0000>PASS</font>，先將公環資料紀錄於活動中，方便您之後要尋找要綁定的公環號。

	![](images/bf.png)

20. 點擊<font color = #ff0000>PASS</font>匯入成功時會跳出的視窗。

	![](images/be.png)

21. 當該GPS環並未設定放飛時，會跳出一個小視窗告訴您此狀況。

	![](images/bd.png)

23. 當您再匯入資料前發現有誤時，可以點擊<font color = #ff0000>Reset</font>按鈕，會清除<font color = #ff0000>公環欄位及GPS ID欄位</font>上的資料。

	![](images/bg.png)

24. 完成綁定後您可以回到👉 [skyleader3.0網頁](https://sport.skyleader.com.tw/Home/login)上，查看綁定的腳環及公環。

	![](images/bz.png)

## 讀取GPS

1. 點擊<font color = #ff0000>左邊的放大鏡圖示</font><img src = images/71.png width="40" height="auto">，進入讀取功能的介面。

	![](images/bh.png)

2. <font color = #ff0000>讀取</font>介面的使用方式與<font color = #ff0000>設定放飛</font>一樣，如想返回去看可點擊這裡:point_right:[設定放飛](#設定放飛)返回觀看。

**<div style="background: #e6f7ff; padding: 10px; border-radius: 5px; border: 1px solid #91d5ff;"> :star:請確定點擊完圖示後，右邊的按鈕是否為紅色<font color = #ff0000>讀取</font>按鈕。<br>  :star:<font color = #ff0000>若讀取腳環時，忘記到"讀取"介面，按成設定放飛，原要讀取的軌跡、資料則會被清除。</font> </div>**

![](images/bj.png)

3. 完成讀取後請您回到:point_right: [skyleader3.0網頁](https://sport.skyleader.com.tw/Home/login)上，進行查看軌跡的程序。

<img src = "images/ca.png" width="800" height="auto">

<img src = "images/bk.png" width="800" height="auto">

