# python 自動插圖

- 1x.py適合橫式的電腦截圖，單排一頁會插兩張
- 2x.py適合直式的手機截圖，雙排一頁會插四張
- 1x_filename.py跟2x_filename.py跟上面一樣功能，只是數字編號改為抓取檔案名稱，請自行在命名檔案時加入編號，如「1 手機微信與XXX對話」、「2 手機微信與XXX通話」 等

## how to use

- 安裝[python3.8](https://www.python.org/downloads/)
- 下載整個程式碼
- 安裝函式庫 pip install python-docx（會自動連lxml一起安裝）
- 把圖片放到captures資料夾內
- 執行py檔
- 會產出結果的output檔案

## 內網擋pip狀況

- 需要手動安裝docx與lxml
- （安裝python-docx）把docx.rar解壓縮到[你安裝python的路徑]/Lib/site-packages底下
- （安裝lxml）把lxml-4.5.0-cp38-cp38-win32.whl複製到[你安裝python的路徑]/Scripts底下，在[你安裝python的路徑]/Scripts執行pip install lxml-4.5.0-cp38-cp38-win32.whl
- Done!

## 注意

- 不要動到template(dont-touch-it).docx，這個檔案是用來先插入頁碼的，因為python-docx函式庫貌似沒有支援頁碼
- 如果你安裝到別的版本的python，手動安裝lxml那邊可能會失敗，要來[這邊](https://pypi.org/project/lxml/#files)下載對應的版本