所為何來
=
於 Ubuntu 上安裝 cURL 工具，便可使用 curl 指令透過 HTTP、FTP 等網路協定來傳送檔案。

使用環境
=
Ubuntu Server 12.04

安裝方式
=
於終端機中，輸入以下指令即可：
```bash
sudo aptitude install curl
```
DONE.
<br>
<br>

補充說明
=
* 與 wget 類似的是，都可用來下載檔案；不同的是，cURL 支援帳密登入，還能上傳檔案，並可使用萬用字元來完成批次傳輸。

參考資源
=
* [curl and libcurl](http://curl.haxx.se/) - cURL 的專案開發網站
* [Ubuntu – 在 precise 中的 curl 套件詳細資訊](http://packages.ubuntu.com/precise/curl)
