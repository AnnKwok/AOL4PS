This dataset is distributed for NON-COMMERCIAL RESEARCH USE ONLY. 

Brief description:

The dataset is suitable for personalized search tasks and is built based on AOL query logs.

The dataset contains 3 files.
1. data.csv:  Real query log data that is based on real users for 3 months.
        AnonID - an anonymous user ID number.
        QueryIndex  - the index of  query issued by the user
        QueryTime - the time at which the query was submitted for search.
        SessionNo - the number of sessions
        DataType - 0,1,2,3 representes historical data,train data, valid data, test data respectively
        DocIndex - the index of document clicked by the user
        CandiList - the candidate document list for query issued by user 
        ClickPos - the position of clicked document in candidate document list

2. query.csv: The content and index of query.
        Query - the content of query issued by the user
        QueryIndex - the index of query

3. doc.csv: The content and index of document.
        Url - the url of document clicked by the user
        DocIndex - the index of document
        Title - the title of Url
