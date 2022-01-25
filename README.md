# What's the differences from the main branch?
Here we download specific file from USPTO API.
It's JSON format.

# Update List:
1. 直接從USPTO提供的API要求特定的Patent File ("https://developer.uspto.gov/ibd-api/#!/bulkdata/searchPublicationData" )
2. 將存取下來的JSON格式檔案轉Pandas Dataframe，挑選特定資訊存成CSV檔案，同時將後面語意處理需要做的Claims部分存成Dict。
3. Claims做NLP處理(後續步驟同Prototype)。
