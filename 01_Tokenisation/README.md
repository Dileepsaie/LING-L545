1. Why should we split punctuation from the token it goes with ?

The process of dividing a continuous stream of text into individual tokens, which are the fundamental building blocks of meaning in a language, is known as tokenization. These tokens can take the form of words, numbers, symbols, or any other component that the text is composed of. In most cases, tokenization is accomplished by dividing the text based on whitespace and punctuation marks.

a) It is simpler to apply processing steps in a consistent manner to the text when the tokens and punctuation are kept in separate locations. If you want to lowercase all of the words in a piece of text, for instance, you will have an easier time doing so if the punctuation is already separated from the words.

b) If you separate the punctuation from the tokens in the text, you may make it much simpler to read and comprehend.

c) If we can distinguish between tokens and punctuation, it will be much simpler to make use of the NLP libraries and tools.

Q2. Should abbreviations with space in them be written as a single token or two tokens? How about numerals like 134 000 ?

I believe it is dependent on the situation as well as the particular NLP assignment that we are working on right now. It is possible that it is more suitable to consider abbreviations with spaces to be a single token in some circumstances, whilst in other circumstances, it is possible that it is more reasonable to consider them to be two independent tokens. It is important to note that the value "134 000" should be interpreted as a single token.

Q3. If you have a case suffix following punctuation, how should it be tokenised ?

In circumstances like this, I believe they should be counted as two separate tokens. We are able to accurately capture the meaning of the text as well as its structure if we consider case suffixes to be different tokens. Additionally, this may be useful in POS labelling
Additionally, this may be useful in POS labelling

Q4. Should contractions and clitics be a single token or two (or more) tokens ?

It's an example of a contraction term, along with "can't" (which stands for "cannot"), "won't" (which stands for "will not"), and "it's" (for it is). The letters "ve" (which stand for "have") and "re" (which stand for "are") are both examples of clitics in the English language. Depending on the circumstances, they can be tokenized into two, three, or even more tokens.
