# Chat messages and matchmaking
## Finding the perfect match using text classification on my own message history
### Abstract
We explore the messages from Facebook's "Download your data" section and try to find useful information for text classification. We extract all the links, emoticons, emojis and we separate words into three different categories - English, Bulgarian, and Bulgarian written in latin. All words are checked for validity in a wordlist and processed by transliterating, stemming and stopwords elimination. Multinomial naive bayes is used for classifying messages by sender name and deliberately missclassificating my own messages as another sender.
