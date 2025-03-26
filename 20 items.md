    const courseItems = [
      {
        id: 1,
        title: "Python 基礎",
        level: "入門",
        domain: "基礎",
        description: "介紹python基本知識，輸出、變數、數字的四則運算、輸入的用法。",
        tags: ["基礎語法", "數據類型", "操作符"],
        imageUrl: "public/src/Pic-01.png",
        videoUrl: "https://www.youtube.com/watch?v=cJ_yQb5rmR8"
      },
      {
        id: 2,
        title: "控制結構",
        level: "入門",
        domain: "基礎",
        description: "介紹python基本知識，資料型態、bool, list, 型態轉換、if表達式、for迴圈處理、while迴圈處理的用法。",
        tags: ["基礎語法", "if,elif,else 語句", "for 迴圈", "while 迴圈","book:],
        imageUrl: "public/src/Pic-02.png",
        videoUrl: "https://www.youtube.com/watch?v=winKwQwqt5c"
      },
      {
        id: 3,
        title: "函數和模組",
        level: "入門",
        domain: "基礎",
        description: "了解如何定義和調用函數，並學習如何使用和創建模組來提高程式的可重用性。",
        tags: ["基礎語法", "函數定義", "模組導入", "代碼重用"],
        imageUrl: "public/src/Pic-03.png",
        videoUrl: "https://www.youtube.com/watch?v=FzLjrHDjAz4"
      },
      {
        id: 4,
        title: "資料結構",
        level: "中級",
        domain: "基礎",
        description: "深入學習 Python 的資料結構，包括列表、元組、集合和字典的使用。",
        tags: ["基礎語法", "列表", "元組", "集合", "字典"],
        imageUrl: "public/src/Pic-04.png",
        videoUrl: "https://www.youtube.com/watch?v=3-pVZTczaBA"
      },
      {
        id: 5,
        title: "文件操作",
        level: "中級",
        domain: "基礎",
        description: "學習如何讀取、寫入和處理文件，以管理資料和持久化數據。",
        tags: ["數據處理", "文件讀取", "文件寫入", "數據持久化"],
        imageUrl: "public/src/Pic-05.png",
        videoUrl: "https://www.youtube.com/watch?v=uYkGAg9iBmo"
      },
      {
        id: 6,
        title: "錯誤和異常處理",
        level: "中級",
        domain: "基礎",
        description: "介紹如何使用 try-except 語句來捕捉和處理異常，以提高程式的穩定性。",
        tags: ["測試與調試", "try-except", "異常捕捉", "錯誤處理"],
        imageUrl: "public/src/Pic-06.png",
        videoUrl: "https://www.youtube.com/watch?v=hpQz-0q5uGY"
      },
      {
        id: 7,
        title: "物件導向編程",
        level: "中級",
        domain: "基礎",
        description: "理解物件導向編程的核心概念，包括類和對象、繼承和多態。",
        tags: ["基礎語法", "類和對象", "繼承", "多態", "封裝"],
        imageUrl: "public/src/Pic-07.png",
        videoUrl: "https://www.youtube.com/watch?v=LQZLeYQEzkM"
      },
      {
        id: 8,
        title: "標準庫和第三方庫",
        level: "中級",
        domain: "基礎",
        description: "學習如何使用 Python 標準庫以及安裝和使用第三方庫來擴展應用功能。",
        tags: ["基礎語法", "標準庫", "pip", "第三方庫", "套件管理"],
        imageUrl: "public/src/Pic-08.png",
        videoUrl: "https://www.youtube.com/watch?v=2oCFSBlJ-PA"
      },
      {
        id: 9,
        title: "正則表達式",
        level: "中級",
        domain: "數據",
        description: "掌握正則表達式的使用，以便進行模式匹配和文本處理。",
        tags: ["數據處理", "模式匹配", "文本處理", "re 模組"],
        imageUrl: "public/src/Pic-09.png",
        videoUrl: "https://www.youtube.com/watch?v=CpW8sLapu1g"
      },
      {
        id: 10,
        title: "網絡編程",
        level: "中級",
        domain: "網頁",
        description: "介紹如何利用 Python 進行網絡請求、REST API 操作和數據抓取。",
        tags: ["網頁開發", "HTTP 請求", "REST API", "requests 庫"],
        imageUrl: "public/src/Pic-10.png",
        videoUrl: "https://www.youtube.com/watch?v=sUzR3QVBKIo"
      },
      {
        id: 11,
        title: "數據分析基礎",
        level: "中級",
        domain: "數據",
        description: "使用 Pandas 和 NumPy 進行數據處理、分析及處理大數據的基礎。",
        tags: ["數據處理", "Pandas", "NumPy", "數據分析"],
        imageUrl: "public/src/Pic-11.png",
        videoUrl: "https://www.youtube.com/watch?v=XTXR8za1HYM"
      },
      {
        id: 12,
        title: "數據可視化",
        level: "中級",
        domain: "數據",
        description: "學習如何使用 Matplotlib 和 Seaborn 進行數據可視化，幫助理解數據。",
        tags: ["數據處理", "Matplotlib", "Seaborn", "圖表繪製"],
        imageUrl: "public/src/Pic-12.png",
        videoUrl: "https://www.youtube.com/embed/a9UrKTVEeZA"
      },
      {
        id: 13,
        title: "Web 開發基礎",
        level: "中級",
        domain: "網頁",
        description: "使用 Flask 或 Django 框架建立簡單的 web 應用程序，了解後端開發。",
        tags: ["網頁開發", "Flask", "Django", "後端開發"],
        imageUrl: "public/src/Pic-13.png",
        videoUrl: "https://www.youtube.com/embed/Z1RJmh_OqeA"
      },
      {
        id: 14,
        title: "測試和調試",
        level: "中級",
        domain: "基礎",
        description: "學習如何使用單元測試和調試工具，保證代碼質量和可靠性。",
        tags: ["測試與調試", "單元測試", "unittest", "調試技巧"],
        imageUrl: "public/src/Pic-14.png",
        videoUrl: "https://www.youtube.com/watch?v=s83zs3wLOEo"
      },
      {
        id: 15,
        title: "API 開發",
        level: "進階",
        domain: "網頁",
        description: "學習如何使用 Flask-Restful 開發 RESTful API，並與前端交互。",
        tags: ["網頁開發", "RESTful API", "Flask-RESTful"]
        imageUrl: "public/src/Pic-15.png",
        videoUrl: "https://www.youtube.com/watch?v=KjQXByQLMyE"
      },
      {
        id: 16,
        title: "機器學習基礎",
        level: "進階",
        domain: "人工智能",
        description: "全面理解機器學習的原理，利用機器學習作分析、預測，並使用pytorch搭建模型。",
        tags: ["人工智能", "pytorch", "模型訓練", "預測分析"],
        imageUrl: "public/src/Pic-16.png",
        videoUrl: "https://www.youtube.com/watch?v=wm9yR1VspPs"
      },
      {
        id: 17,
        title: "自然語言處理",
        level: "進階",
        domain: "人工智能",
        description: "處理真實數據時可能遇到的挑戰和解決方案。透過這個影片，您將獲得對NLP專案的全面理解，並掌握建立有效NLP應用的基本技能。",
        tags: ["人工智能", "NLTK", "SpaCy", "文本分析"],
        imageUrl: "public/src/Pic-17.png",
        videoUrl: "https://www.youtube.com/watch?v=h2kBNEShsiE"
      },
      {
        id: 18,
        title: "電腦應用程式開發",
        level: "中級",
        domain: "中級",
        description: "使用 Tkinter 開發簡單的桌面應用程序，掌握 GUI 編程基礎。",
        tags: ["基礎語法", "Tkinter", "GUI 編程", "桌面應用"],
        imageUrl: "public/src/Pic-18.png",
        videoUrl: "https://www.youtube.com/watch?app=desktop&v=IXQWVM46-zg&t=214s"
      },
      {
        id: 19,
        title: "爬蟲技術",
        level: "中級",
        domain: "數據",
        description: "學習使用Scrapy 進行網頁爬蟲，提取網頁數據。",
        tags: ["數據處理",  "Scrapy", "網頁數據提取"],
        imageUrl: "public/src/Pic-19.png",
        videoUrl: "https://www.youtube.com/watch?v=u-1PURwCMxE"
      },
      {
        id: 20,
        title: "數據庫操作",
        level: "中級",
        domain: "數據",
        description: "使用 SQL、MySQL 和資料庫管理相關的基本概念和實用技能。",
        tags: ["數據處理", "SQLite", "SQLAlchemy", "CRUD 操作"],
        imageUrl: "public/src/Pic-20.png",
        videoUrl: "https://www.youtube.com/watch?v=gvRXjsrpCHw"
      }
    ];
