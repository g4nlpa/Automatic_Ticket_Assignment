# Automatic_Ticket_Assignment

1)Removed the column Caller

2)Filled missing values

3)Preproccesing steps
  a)Remove html tags
  b)Remove non-ASCII characters
  c)Convert to lower case
  d)remove punctuation
  e)remove whitespaces
  f)remove  digits
  g)remove emails  
  h)remove hyperlinks
  i)remove other characters 
  
4)Translated all the entries to english

5)Meaningless words,names,non latin characters etc were removed

6)Stopwords removed

7)Expand Contractions

8)Spelling correction

THE ENTIRE PREPROCESSED DATA IS SAVED AS A PICKLE FILE.IF YOU DONT WANT TO RUN THE PREPROCESSING FROM SCRATCH(TAKES AROUND 4 HOURS)
LOAD THE preprocesseddata.pkl USING A SIMILAR FORMAT AS BELOW:

df=pd.read_pickle('preprocesseddata.pkl')

