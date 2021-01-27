# dsiprojects

### 
---
1  Introduction & Problem Statement
Reddit is a social media website focused on social news aggregation, web content rating, and discussions. Members contribute content through different subreddits(community-managed pages) that are then voted up or down by other members of the community. Scored through an algorithm that measures votes and among other things time that the post has been there, which assures that new content will always float to the top. Submissions with a high enough score will make it to the front page of reddit. Reddit's subreddits have created interesting niche communities that have flourished and may not have survived on other parts of the internet.

Reddit/r/AmitheAsshole is one such niche community that has arisen with a unique premise that aims to both help and entertain users. The premise is such, people post situations that they have found themselves in in which they feel they will be perceived as an 'asshole'. Commenters reply to the original posters situation and vote on them by using coded language designated in the subreddit rules. There are times, however, that posters can't make up their minds, and leave some form of vaguely worded message with a conflicting vote.

This project aims to create a model that can use comments to predict on comments that contain both YTA & NTA.

In order to explore the possibilites of NLP, I used several forms of Lemmatization to process text. I created 4 different points of data

Cleaned_word : Simple cleanup of text, only alphabets without punctuation
Nltk_lem : Using NLTK word lemmatizer 
Nltk_pos : Using NLTK pos tagger to help filter & Lemmatize text 
Spacy_lem : Using Spacy word lemmatizer 

### Summary of Findings & Recommendations
---
In conclusion, through training on 4 types of text processing using a variety of vectorizers and classifers I identified a model that predicted if a person would vote YTA or NTA to a 85.9% beating out the baseline accuracy of 77%. Although more advanced techniques were used in the lemmatization of the text, the simplest text model beat out most of the other models.

The end model seems to pick up reliably on the text. For example, in the above comment, the model was able to pick up on the language use although active strong language was used. From the extraction of the coefs, I would assume the model would recognize such language use as 'YTA' rather than the strong 'NTA" the post was given.

Due to time restraints many of the aspects of the project were not explored. Future improvements to the project could be to access the post texts to do a word study between the comments and the original post, common words used between the two for example.
