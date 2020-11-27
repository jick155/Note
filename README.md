# 下單機安裝程序

## 軟體安裝

1.安裝條件
* 需有python環境
* 需有群益卷商憑證
* 需有群益api元件
* IDE x64 (Notepad++)(https://notepad-plus-plus.org/downloads/v7.8.8/) 可選
* 憑證安裝(私密性)


## python 安裝
    Anaconda 3目前有三種版本(如下圖)，分別是個人版(Individual Edition)、團隊版(Team Edition)及企業版(Enterprise Edition)

Anaconda 3 安裝 — Individual Edition
首先，我們先到Anaconda官網(https://www.anaconda.com/)，點選上方 Products/Individual Edition 。
![image alt](https://miro.medium.com/max/1000/1*DXsRG9KV01AgPlauQp9k-Q.png)
在個人版本(Individual Edition)介紹頁中，您將可以看到相關特色說明，看完後您可以點選「Download」，畫面將會帶您到頁面下方下載區。
![image alt](https://miro.medium.com/max/1000/1*Jx7ElpDcPTxI9YMbPQry_Q.png)
在此下載頁面區塊中，將會呈現支援各種不同作業系統(有 Windows、MacOS 及 Linux 可選擇)的Anaconda版本，每個作業系統針對 Python 3.7 / Python 2.7 都有64位元(64-Bit)及32位元(32-Bit)不同版本可提供，讀者可以根據自己需求做不同下載版本選擇。
1. 下載 Anaconda Installer
本篇文章將針對 Windows 作業系統，下載 Python 3.7 / 64-Bit 的 Installer 來做安裝說明。
![image alt](https://miro.medium.com/max/1000/1*dcthSWlyQdsxMqwx4rC47g.png)
2. 執行下載的 Anaconda installer
![image alt](https://miro.medium.com/max/1000/1*KsfRuw0VHYCWpZjehk4yww.png)
3. 查看安裝版本，並點選「Next」
![image alt](https://miro.medium.com/max/700/1*wAAtTiAcXI6T8-BxWdYzHA.png)
4. 閱讀許可協議(License Agreement)後，點選「I Agree」
![image alt](https://miro.medium.com/max/700/1*rfzXF-LCy3nMPlvCUtI52g.png)
5. 選擇欲安裝對象
會有兩種選擇如下，
○ Just Me (系統建議)
○ All Users
除非需要為系統的所有用戶(需要Windows管理員權限)進行安裝，否則可依系統建議，選擇" Just Me "安裝即可，並點選「Next」
![image alt](https://miro.medium.com/max/700/1*L2JYA9x2PSAkKBbbdAHiuw.png)
6. 確認安裝路徑
若需要更改Anaconda預設的安裝路徑，可點選「Browse」進行選擇欲安裝位置，若沒有要變更可直接點選「Next」
![image alt](https://miro.medium.com/max/700/1*4PfhldFLe5onyvnIwwEs3w.png)
7. 進階選項安裝
選擇是否要將 Anaconda 加到 PATH 環境變數中，若不確定您自己的需求，可參考官方建議不用將 Anaconda 加到環境變數裡，依預設勾選選項並直接點選「Install」
![image alt](https://i.imgur.com/GK5wW43.png)

8. 進行安裝
在安裝過程中，若想要查看安裝那些細項，可以點選「Show details」
![image alt](https://miro.medium.com/max/700/1*2DmWy4r6JZ5qS1wsuek0MA.png)
點選「Show details」後，將可看到系統安裝資訊過程，並等待安裝。
![image alt](https://miro.medium.com/max/700/1*y-vfnSR4c7_NIj_wgbwBLQ.png)
9. 安裝完成
安裝完成前，會顯示訊息除了安裝 Anaconda 外，同時也安裝 JetBrains 這家軟體公司的 PyCharm IDE，並完全與 Anaconda 整合起來，方便您在開發時使用，點選「Next」。
![image alt](https://miro.medium.com/max/700/1*omFpirLPCyMeAY5sMtxe7g.png)
您將看到已完成安裝的訊息，若不想看一些說明，可將check box前的勾勾拿掉，並點選「Finish」即完成 Anaconda 3的安裝。
![image alt](https://miro.medium.com/max/700/1*vqqfeR4xytG4oN2iePPVqg.png)
10. 驗證安裝是否完成
安裝完成後，我們可以做一個簡單的檢查來確保安裝沒有問題。讀者可以試著從 Windows 左下角的開始選單(Start menu)中，選擇 Anaconda 3 (64-bit)資料夾下的 Anaconda Navigator (anaconda 3)。
![](https://i.imgur.com/WZbU5b4.png)




# 下單機安裝
1. 兩種方式
## 公司碟(SVN Project)
*         Projects\Doquant\Platform\DoOrderMachine # 路徑
![image alt](https://i.imgur.com/XT7zDic.png)
        全部複製並且貼上於工作目錄(桌面or資料夾)

下載完成後，解壓縮後，進入x64資料夾，滑鼠右鍵
![](https://i.imgur.com/DJeCYvK.png)
點選系統管理員執行，然後點選是
![](https://i.imgur.com/4GFMvSA.png)
安裝成功-->
![](https://i.imgur.com/WxRgr5x.png)

接下來在這裡輸入 cmd ，然後會出現小視窗。
![](https://i.imgur.com/891zGdt.png)

複製程式碼貼上
```
pip install -r requirements.txt

```

跑完後，輸入程式碼

```
python DQO.py
```
出現這個畫面--完成度**90%**
![](https://i.imgur.com/NPW38eg.png)

測試一 : 輸入帳號 'DL'
![](https://i.imgur.com/H1P6ndB.png)
點選訂閱策略會出現以下圖片的畫面
![](https://i.imgur.com/sDa12y9.png)
點選**設定進出場條件**
![](https://i.imgur.com/yr7HCPv.png)
更改設定值，儲存後重來是否一致。

測試二 : 

需有證卷帳號，待設計。






## 個人分享網站
網址 ([link](https://192.168.233.133:8080/)) 帳號:admin 密碼 : ADMIN

```
路徑--> financial-->DoquantRelease
```
![](https://i.imgur.com/0StxhyH.png)

滑鼠移到資料夾旁邊有個小框，點選兩個後
![](https://i.imgur.com/9dACv7t.png)

點擊下載
![](https://i.imgur.com/F0gO97Y.png)


下載完成後，解壓縮後，進入x64資料夾，滑鼠右鍵
![](https://i.imgur.com/DJeCYvK.png)
點選系統管理員執行，然後點選是
![](https://i.imgur.com/4GFMvSA.png)
安裝成功-->
![](https://i.imgur.com/WxRgr5x.png)

接下來在這裡輸入 cmd ，然後會出現小視窗。
![](https://i.imgur.com/891zGdt.png)

複製程式碼貼上
```
pip install -r requirements.txt

```


![](https://i.imgur.com/IYIhjJn.png)

跑完後，輸入程式碼


```
python DQO.py
```



![](https://i.imgur.com/hlkqW2W.png)

出現這個畫面--完成度**90%**
![](https://i.imgur.com/NPW38eg.png)

測試一 : 輸入帳號 'DL'
![](https://i.imgur.com/H1P6ndB.png)
點選訂閱策略會出現以下圖片的畫面
![](https://i.imgur.com/sDa12y9.png)
點選**設定進出場條件**
![](https://i.imgur.com/yr7HCPv.png)
更改設定值，儲存後重來是否一致。

測試二 : 

需有證卷帳號，待設計。

## RegSvr32 安裝失敗

當Windows Server註冊dll出現以下訊息:
1.	無法載入模組：
![](https://i.imgur.com/wL3tjk9.png)
Step 1請確定註冊SKCOM.dll 時，以下相關憑證等(＊.dll) DLL檔案是否完整。
![](https://i.imgur.com/XdJ2vWI.png)
若上述檔案列表與您的資料夾相同，再進行▼step 2.
Step 2請注意是否遺失或缺少mfc100u.dll，並安裝下面所列套件
![](https://i.imgur.com/Vdyq1YG.png)
![](https://i.imgur.com/gfjXgqO.png)
▼（下列連結，請依微軟Microsoft Visual C++ 2010 SP1可轉散發套件最後更新版本為主，下列link僅供參考）

* Microsoft Visual C++ 2010 Service Pack 1 MFC 可轉散發套件的安全性更新
https://www.microsoft.com/zh-tw/download/details.aspx?id=26999 
* Microsoft Visual C++ 2010 SP1可轉散發套件 (x86)
https://www.microsoft.com/zh-tw/download/details.aspx?id=8328
* Microsoft Visual C++ 2010 SP1可轉散發套件 (x64)
https://www.microsoft.com/zh-tw/download/details.aspx?id=13523
x86位元:直接註冊即可
x64位元:透過SysWow64的regsvr32.exe註冊


## 憑證安裝

當發生代碼:1045 =憑證尚未申請，須走以下流程

[群益憑證連結](https://www.capital.com.tw/Service2/certificate2/)

沒有申請過就點選申請，其餘用備份/匯入
![](https://i.imgur.com/ypTaZER.png)

輸入您的帳號密碼做憑證匯入
![](https://i.imgur.com/ajDGHOb.png)

匯入成功如圖所示:
![](https://i.imgur.com/XUYj5Fa.png)




