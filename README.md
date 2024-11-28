![image-removebg-preview-2](https://github.com/user-attachments/assets/da44b219-f6a0-438e-a7fb-5a0cc7c960df)
# Kumlinda
Fortifying Community Truth: Developing Lexicons on Tech Facilitated GBV and Model for Low-resourced African Languages ( Hausa, Igbo, Yoruba and Swahili) 
African languages are spoken by over a billion people, but they are under-represented in NLP research and development. Multiple challenges exist, including the limited availability of annotated training and evaluation datasets as well as the lack of understanding of which settings, languages, and recently proposed methods like cross-lingual transfer will be effective. Perpetrators of TFGBV (Tech-Facilitated Gender Based Violence) have used local nuances online to target women and girls, many generic or non-African model not trained on these languages have performed poorly in flagging some of these words on social media, we aim to move towards solutions for these challenges, focusing on the task of named entity recognition (NER). We present the creation of the largest to-date human-annotated NER corpus used on social media to target the female gender in four African languages (Hausa, Igbo, Yoruba, and Swahili).

## Supported Languages

 Language      | ISO 639-2 code
 ------------- | -------------
Hausa	| hau
Igbo	| ibo
Yoruba	| yor
Swahili	| swa

## Attributes

 Attribute      | Contextualisation
 ------------- | -------------
Sexually Explicit	| Comments expressing desire for genital nudity or depictions or descriptions of simulated or actual sexual acts.
Vulgarity	| Making explicit and offensive reference to sex or bodily functions.
Insult	| Remarks that include offensive and disrespectful words.
Flirtation	| Statements demonstrating inappropriate sexual advances with the intent to arouse sexual feelings.
Misogyny/Gender Trolling	| Passing sexist remarks, jokes, and memes, expressions treating women like objects, stereotyping women, sending unsolicited pornographic contents.

## Formats

All the data and associated metadata together in one file will be available in csv and json file formats.

`Kumlinda.csv` - data and associated metadata in csv format.

`Kumlinda.json` - data and associated metadata in json format.

Below is an example row.

```json
{
   "data":{
      "eng":"Her pussy would have been insanely expanded, Damn.",
      "hau":"Da an fadada farjinta da hauka, Damn",
      "ibo":"Ọtụ ya gaara agbasawanye nke ukwuu, Damn",
      "yor":"Òbò ma ti fẹ̀ bi olóríburúkú, Damn.",
      "swa":"Pussy yake ingekuwa imepanuliwa kichaa, Damn",
   },
   "metadata":{
      "scope":"Africa",
      "category":"Romance",
      "source":"https://www.nairaland.com/8248492/former-adult-film-actress-riley",
      "attribute":"vulgarity",
      "date":"2024-10-24"
   }
}

````
# Post surface
```
FaceBook Results include those posted from the specified endpoints.

```

Profiles: Posts that appear on profiles set to public with a verified badge or 25,000 or more followers

Pages: Posts that appear on public Pages, posted by anyone

Events: Posts that appear on public events, posted by anyone

Groups: Posts that appear on public groups, posted by anyone

```
Instagram Account type: Results include those posted from the specified endpoints.

```

Personal: Accounts set to public with a verified badge or 25,000 or more followers

Business: Accounts with access to tools to grow and reach customers

Creator: Accounts for content creators, artists and influencers

#### 1. [Manually Annotated Social Media Sentiment Dataset]
#### 2. [Semi-automated Annotated Social Media Sentiment Lexicon]

### Translation Team

#### Swahili

- Nyakerario Omari
- Joan Muthoki Kithanze

#### Hausa

- 
- 

#### Igbo

- Ada 
- Ehis

#### Yoruba

- Israel Olatunji Tijani
- Salvation Grace

# OpenSource Articles

CommonCrawl is a non-profit organization which provides web crawl data for free. Their datasets are used by various organizations, both in academia and industry,
as can be seen on the examples page. The applications range from machine learning to natural language processing or computational linguistics.
[Common Crawl](https://commoncrawl.org/use-cases)

## Model 


This model is available via Kaggle Model Hub [here](https://www.kaggle.com/)


## 🚀 Deployment

The live version is hosted on [GitHub](https://github.com) and [Kaggle](https://kaggle.com).
The pre-trained model is found in `main.py`.

## Contact me

If you want to report a problem or suggest an enhancement, crowdsourcing contributors is welcomed. Reach me via email (israel@chatve.co) or on [X](https://x.com/Holatung).
