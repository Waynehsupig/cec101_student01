"# DjangoForFun" 

# 注意事項
1. 請pull dev的branch然後去開發, 若要commit或merge也都到這一條branch
2. 先確認有python和套件管理pip環境, 若沒有就先安裝, 安裝完再從virtualenv創出的虛擬環境安裝django
3. 使用pycharm開發的話, 因為pycharm會幫你開個虛擬環境, 就不用再另外去pip install virtualenv
4. 若下python mange.py runserver, 執行src資料夾內mange.py, 就可以運行此Web application
5. src為web的root
6. 循序圖
```seq
User->urls.py: Tap button
urls.py->view.py: Find the specific function
view.py-->>User: Return value
```
7. 在寫view.py裡的function時, 可以想一下如何寫個單元測試, 驗證一下輸入/輸出參數
8. 目前先這樣, 之後會再補充
