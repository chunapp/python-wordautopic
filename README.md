# python 自動插圖 1x


## How to
- 安裝[python3.8](https://www.python.org/downloads/)
- 下載整個程式碼
- 安裝函式庫 pip install python-docx
- 把圖片放到captures資料夾內
- 執行capture.py
- 會產出結果的output檔案

## 內網擋pip狀況
- 需要手動安裝docx與lxml
- 把docx.rar解壓縮到[你安裝python的路徑]/Lib/site-packages底下
- 把lxml-4.5.0-cp38-cp38-win32.whl複製到[你安裝python的路徑]/Scripts底下
- 在[你安裝python的路徑]/Scripts執行pip install lxml-4.5.0-cp38-cp38-win32.whl
- Done!

## 注意
- 不要動到template(dont-touch-it).docx
- 如果你安裝到別的版本的python，手動安裝lxml那邊可能會失敗，要來[這邊](https://pypi.org/project/lxml/#files)下載對應的版本