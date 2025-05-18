# text_preprocessing_for_nlp
In this repo a pipeline has been created that handles messy input texts and converts them into processible tokens

1. Punctuations were not removed in the first hand. Instead, multiple punctuations like !!!, ...., @#$% were replaced with "strong emotion" as they might show intense emotions
2. Emojis are also converted into their specified texts which can also preserve the customer's emotion or sentiment
3. Then the corpus was coverted lowercase and tokenized
4. A customized slang dictionary was created to handle the abbreviations
5. Lemmatization was used as it can preserve the context which is important to understand client situation
