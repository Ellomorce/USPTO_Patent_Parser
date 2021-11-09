# What is this??
NTUT-Data Science-Project: Patent Parser

# Who own the project?
Group 6
110C51505 張仁程
110C51537 王星文
110C51522 謝安
110C51526	蔡侑芯
110C51533	陳毓庭
110C51520	楊文均

# Update List:
1. 讓程式碼在Windows/Linux環境下可執行抓取Xml File的動作。
2. 使用Beautifulsoup 抓取關鍵資訊包括 "Patent Number", "Publication Date", "Application Date", "Country", "Application Type", "Title", "Abstract", "Applicant", "Inventor", "IPCs"。
3. 使用Pandas製作表格。
4. 使用Pandas匯出CSV檔 (或匯入關聯式資料庫)。
5. 使用Beautifulsoup 抓取Patent Claims。
6. 使用nltk處理對Patent Claims進行自然語言處理，tokenization、lemmatization、然後NER(POS Pattern)只抓取出名詞，並把資料存成dict。
7. 萃取dict中使用率前50的名詞並使用matplotlib進行視覺化。
8. (還沒做)將dict轉換成多維向量(dict中50個字是向量、使用次數是其分量)，然後跑correlation。
9. 將8.視覺化
