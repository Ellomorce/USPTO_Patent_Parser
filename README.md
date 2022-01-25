# Update List:
1. 讓程式碼在Windows/Linux環境下可執行抓取Xml File的動作。
2. 使用Beautifulsoup 抓取關鍵資訊包括 "Patent Number", "Publication Date", "Application Date", "Country", "Application Type", "Title", "Abstract", "Applicant", "Inventor", "IPCs"。
3. 使用Pandas製作表格。
4. 使用Pandas匯出CSV檔 (或匯入關聯式資料庫)。
5. 使用Beautifulsoup 抓取Patent Claims。
6. 使用nltk處理對Patent Claims進行自然語言處理，tokenization、lemmatization、然後NER(POS Pattern)只抓取出名詞，並把資料存成dict。
7. 萃取dict中使用率前50的名詞並使用matplotlib進行視覺化，生成長條圖，然後存成1200x900的PNG檔案。
8. 使用了Google USE跑語義相似度，並更換了一下顏色並存成PNG檔案。

References:
1. https://medium.com/analytics-vidhya/best-nlp-algorithms-to-get-document-similarity-a5559244b23b
2. https://www.tensorflow.org/hub/tutorials/semantic_similarity_with_tf_hub_universal_encoder
