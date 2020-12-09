# NLP_Practical_Exam-Text-Summarizer
### **Automatic Extractive Text Summarization using TF-IDF**

In the recent years, information grows rapidly along with the development of social media. With the increasing amount of information, it takes more effort and time to review the entire text document and understand its contents. One possible solution to the above problem is to read the summary of the document. The summary will not only retain the essence of the document, but will also save a lot of time and effort. An effective summary of the document will concise and fluent while preserving key information and overall meaning.

#### **What is TFIDF Approach ?**

TFIDF, short for term frequency–inverse document frequency, is a numeric measure that is use to score the importance of a word in a document based on how often did it appear in that document and a given collection of documents. The intuition behind this measure is : If a word appears frequently in a document, then it should be important and we should give that word a high score. But if a word appears in too many other documents, it’s probably not a unique identifier, therefore we should assign a lower score to that word.
Formula for calculating tf and idf:
TF(w) = (Number of times term w appears in a document) / (Total number of terms in the document)
IDF(w) = log_e(Total number of documents / Number of documents with term w in it)
Hence tfidf for a word can be calculated as:
TFIDF(w) = TF(w) * IDF(w)
