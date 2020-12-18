# projet
<div class="alert alert-warning"> <label style=" font-size: 50px;"> <span style="color:black" >projet : Classification des Tweets</span></label> 
    <h1>Thameur Amal 3DNI1</h1>

</div><br>

<i><h2><span style="color:blue" >Ojectifs:</span></h2></i>
<p style=" font-size: 20px;">•Maitriser l’API de twitter pour l’extraction des tweets<br>
•Maitriser la partie NLP (naturallanguageprocessing) avec NLTK en Python<br>
•Appliquer les principes de nettoyage des données<br>
•Classer les tweets: regrouper ensemble les tweets qui sont similaires.C’est une étape qui peut être considérée comme une étape <br>
</p>
<i><h2><span style="color:blue" >Spécifications</span></h2></i>
<p style=" font-size: 20px;">
Imaginons que vous avez  un compte Twitter, et que vous lez suivre les tweets (texte très court)sur ce réseau social. Vu le nombre colossal de Tweets, et faute de temps, vous n’avezpas la possibilité deleslire  tous.  Pour  cela,  vous  avez  besoin d’une application qui va jouer le rôle d’assistantet quiva  vous effectuer un résumé de toutes ces informations. Une des approchesqu’on peut utiliser estde le classer sous former de groupesde sorte à ce qu’on présente à l’utilisateur un seul Tweet de chaque groupe. Pour cela, on doit procéder en trois grandes étapes:
</p>
<div class="alert alert-info">
    <i><h2><span style="color:blue" > I:Prétraitement des  tweets</span></h2></i>
    
</div>
  <p style=" font-size: 20px;">
  Télécharger  les Tweets à partir de Twitter en utilisant l’API de twitter. Pour cela, vous devriez un compte «Twitter Developer».<br>
* consumer_key = "ry9GMoJRUCdsHo89bkpVosu8T" <br>
* consumer_secret = "y9Yy5X6RE3n6hEogGhVYCmGDKgDPhWuQB8sexc61xKH01Xv6MA" <br>
* access_key = "1330861473481052162-NXO8xkGNxf0g6A7wbOjOfMPKZrfUvT" <br>
* access_secret = "20Ye373RjvjjMfpbPHAW6kbwJURRbqRaQsnMYFBCrZpyw"<br>
    </p>
  <h1> Libraries </h1><br>
import pandas as pd <br>
import tweepy<br>
import numpy as np<br>
import matplotlib.pyplot as plt<br>
import seaborn as sns <br>
import nltk <br>
import warnings <br>
from nltk.corpus import stopwords <br>
from nltk.tokenize import RegexpTokenizer <br>
from nltk.stem.porter import * <br>
from sklearn.feature_extraction.text import CountVectorizer <br>
from sklearn.cluster import KMeans <br>



