# Automated-Google-Classroom-Creatioin

## 前提 

老師一定要用學校gm帳號，學生一定要有gmail（不一定要gm)

## 步驟

1. 複製[Google Sheet模版](https://docs.google.com/spreadsheets/d/1aTn_dN7Y2HqE286ceAFvXkXkj2NHJwrrLTOu63Vkx-U/edit?usp=sharing)（選單**File > Make a copy**)將檔名改成你的課名（之後創好的classroom會同名稱）。
2. 將Google Sheet內容換成你的修課名單，一定要有學號，姓名欄位, 其他不重要。  
3. 選單**Extensions > App Scripts**, 開啟App scripts程式開發環境。
4. App scripts選單確認Debug旁是`create_classroom_menu`，如果沒錯按**Run** (中間會有授權需要，請接受），結果後回到Google sheet。
5. Google sheet選單會新增**Classroom**項目。
6. **Classroom > setup ** 會新增你要的classroom, 點<https://classroom.google.com/>會看到新課程等你接受，請接受它。同時會創一個Google Form。
7. **Classroom > connect form** 
8. 你需要把Form公告在classroom讓自己加入課程的同學去填此Form。Form目前只搜集學生email及姓名（含學號末三碼），如有其他個人資訊想一併搜集可以自己增加，但前二項不可刪除。學生填好的個人資料會自動整併到Google sheet修課名單，這樣你就知道classroom誰是誰。

> Google classroom也接受學生不使用gmail登入，但這會有些問題，請同學一定要用gm或一般gmail加入google classroom.  
> Form settings 裡的"Restrict to users in 國立臺北大學 and its trusted organizations"建議關掉，這樣不是使用gm加入課程的學生（即一般gmail）也可以填表。
