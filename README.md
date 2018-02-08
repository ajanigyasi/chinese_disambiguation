### 2016 ACL paper experiment

The Association for Computational Linguistics (ACL) is the premier international scientific and professional society for people working on computational problems involving human language, a field often referred to as either computational linguistics or natural language processing (NLP). In mid-summer 2016, San Diego was a chosen destination for the annual ACL conference where papers are submitted and evaluated. As a new San Diego Native, I decided to read one of the accepted 2016 ACL papers gauging the effectiveness of exploited Chinese characters. Given that this is my first stab at learning the Chinese language, what could possibly go wrong? My goal is to demonstrate how characters and words associated to them can change the conversation, if not used correctly

The idea behind this paper is to show how jointly learned character and word embeddings can capture semantic contribution of characters to words using a similarity-based method. In the Chinese language, characters and words have different part-of-speech labels (e.g. noun, verb, etc.) and yet express the same meaning. Further, characters carry more ambiguity weight than words. To address this issue, the paper proposes multi-prototype character embeddings where different meanings of characters will be represented by different embeddings. Please check out my Jupyter Notebook to understand this paper's functionality and applications. Don't hesitate to correct my code if you know a simplier route to get results.

 #### Paper Sources
*[SCWE](http://www.aclweb.org/anthology/N16-1119)
*[2016 accepted papers](http://naacl.org/naacl-hlt-2016/accepted_papers.html)

#### Data Sources
*[Chinese Wiki Dump](http://download.wikipedia.com/zhwiki/)

