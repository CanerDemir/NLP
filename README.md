*Caner Demir*


#### Detection Author of a Text in Turkish
#####Descripton:
The aim of the project is determining the author of a given text. I try to define  an appropriate characterization of documents that captures the writing style of the authors. Let me explain what I mean by style of the authors; the authors use different words to write something about the same subject or some authors use special sentences many times in their  article, etc. My job is found that words, special sentences of the authors to create their style. When we know the style of an author, we can detect his/her text which unknown author. 

The most important approaches to computer based author identification are exclusively based on lexical measures.
There is an article about author detection [here](http://www.google.com.tr/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0CCAQFjAA&url=http%3A%2F%2Fwww.yildiz.edu.tr%2F~diri%2FICANN.pdf&ei=wRb-VLD7EYKtUbyjgfgC&usg=AFQjCNGeVVAacCuWL2ibkj-QM9j8QNfejQ&bvm=bv.87611401,d.d24).
#####A way to do:
May be I try to write some train models for styling the authors with words or sentences. And then using these models to finding the author of given texts. 
#####Project Requirements:
  Java, The OpenNLP

#####Steps for Done
1. All training set contains 10 different texts for each of some authors.
2. Style marker has been processed for every text of the authors and by having the average of these 10 articles we could collect style markers per author.
3. Creating a word database.The word database module is in the matrix form and in first column there is the word itself, in the second, third and fourth columns there are the grammatical types of the word.
4. As expressed in the word database module each word may have maximum of 3 grammatical types. The system automatically detects the type by implementing the grammatical rules on the sentence.
