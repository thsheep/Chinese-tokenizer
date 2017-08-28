"# Chinese-tokenizer" 

安装：

pip install chinese-tokenizer

使用：

from sklearn.feature_extraction.text import CountVectorizer

from chinese_tokenizer.tokenizer import Tokenizer

jie_ba_tokenizer = Tokenizer().jie_ba_tokenizer

count_vect = CountVectorizer(tokenizer=jie_ba_tokenizer)

个人使用 不保证可用性