"# Chinese-tokenizer" 

from sklearn.feature_extraction.text import CountVectorizer

from chinese-tokenizer.tokenizer import Tokenizer

jie_ba_tokenizer = Tokenizer().jie_ba_tokenizer

count_vect = CountVectorizer(tokenizer=jie_ba_tokenizer)