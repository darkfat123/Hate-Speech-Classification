<!-- PROJECT LOGO -->
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExdGoyZXp1aTdob2RsMm9xY2NnZHdoc3UwbHhnY3hycThqcXh1aHhodSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/sh3y88tgOINC8/giphy.gif" alt="Logo" width="100" height="100">
  </a>

<h3 align="center">Hate Speech Classification</h3>

  <p align="center">
    The machine learning model for separating hate and non-hate comments from Tweets.
    <br />
    <br />
    <a href="https://github.com/darkfat123/Hate-Speech-Classification/issues" target="_blank">🚨 Report Bug</a>
    ·
    <a href="https://github.com/darkfat123/Hate-Speech-Classification/issues" target="_blank">✉️ Request Feature</a>
  </p>
</div>
<img src="https://i.imgur.com/dBaSKWF.gif" height="30" width="100%">

<h3 align="left">About this web application 🙋‍♂️:</h3>

<h4 align="left">Input:</h4>

```python
text = ["Lviv mayor says city is struggling to feed and house 200,000 displaced Ukrainians"]
tweet = vectorizer.transform(text) 
tweet_predict = (model.predict(tweet))
if np.argmax(tweet_predict) == 0: 
    print (text,": Not-Hate")
else:
    print (text,": Hate")
```

<h4 align="left">Output:</h4>

```python
['Lviv mayor says city is struggling to feed and house 200,000 displaced Ukrainians'] : Not-Hate
```

<br />

  * Preprocessing dataset such as special characters.
  * Using relu and sigmoid.
  * The outputs have only hate or not-hate.
<br />

<img src="https://i.imgur.com/dBaSKWF.gif" height="30" width="100%">

<img align="right" alt="Coding" width="250" src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExbnQzbmEzM2dub2o5OHowN2E4dHhmaDhsYnNwbDU3a2lmcm4wdGJ1bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/dhGGpFEXFUN63MVaSR/giphy.gif">
<h3 align="left">Languages and tools used in this web application:</h3>

- Backend
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python" />
  </a>
</p>

<img src="https://i.imgur.com/dBaSKWF.gif" height="30" width="100%">

<h4> Connect with me 🎊: <h4>
  <a href="https://www.linkedin.com/in/supakorn-yookack-39a730289/">
   <img align="left" alt="Supakorn Yookack | Linkedin" width="30px" src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" />
  </a>
  <a href="mailto:supakorn.yookack@gmail.com">
    <img align="left" alt="Supakorn Yookack | Gmail" width="32px" src="https://www.vectorlogo.zone/logos/gmail/gmail-icon.svg" />
  </a>
  <a href="https://medium.com/@yookack_s">
    <img align="left" alt="Supakorn Yookack | Medium" width="32px" src="https://www.vectorlogo.zone/logos/medium/medium-tile.svg" />
  </a>
   <a href="https://www.facebook.com/supakorn.yookaek/">
    <img align="left" alt="Supakorn Yookack | Facebook" width="32px" src="https://www.vectorlogo.zone/logos/facebook/facebook-tile.svg" />
  </a>
   <a href="https://github.com/darkfat123">
    <img align="left" alt="Supakorn Yookack | Github" width="32px" src="https://www.vectorlogo.zone/logos/github/github-tile.svg" />
  </a>
<p align="right" > Created by <a href="https://github.com/darkfat123">darkfat</a></p>
<p align="right" > <img src="https://komarev.com/ghpvc/?username=darkfat123&label=Profile%20views&color=0e75b6&style=flat" alt="darkfat123" /> </p>

