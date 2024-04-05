
# Tourist-Attraction-Recommendation
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1WJL0jMGftX1usXTJqQbWzxMgWk7lBN9X#scrollTo=80SL1lvC3jI_)
<br>
This image-embedding based recommendation system is based on the following steps as charted:

Step 1:
![Untitled presentation (3)](https://github.com/ayanatherate/Tourist-Attraction-Search-and-Recommendation/assets/59755186/66d6508e-4ca1-4431-b976-61fd3f6c1f98)


Step 2:
![Untitled presentation (2)](https://github.com/ayanatherate/Tourist-Attraction-Search-and-Recommendation/assets/59755186/1fa6edc2-d4d3-49dc-a535-3245e9218ed0)



<br><br>
Example output:
<br><br>
![image](https://github.com/ayanatherate/Tourist-Attraction-Search-and-Recommendation/assets/59755186/dd19c7cf-a535-4fa9-87f8-4ee41d329ba5)

<br><br>
<h3>Updates 5th April 2024: </h3>
Added a two-tower based embedding model structure where we take into account place names (embeddings) along with their google images,
while providing recommendations. As lets say, simila tourist spot names might be similar too. For example, 'Jaipur Palace' and 'City Palace', can be similar 
as both are indicative of 'Palace'-s as compared to 'Jaipur Palace' and 'Hill View Point', which are indicative of two different places. 

<br>
By combining the name embeddings along with the existing image embeddings in a combined weighted cosine similarity score, we have more robust predictions.







# Tourist-Attraction-Search
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1i5ORoVsV_ALCCL2h-AsaJQdjIti05D6E#scrollTo=9ec8b992)
  
A separate use-case, I've tried to work on: given a location and a search radius, bring out the top Tourist Spots according to preference (example 'Hills', 'Palaces' etc.)
However, Google Maps has this functionality. If you want to search 'Hills near me' on the Gmaps search bar, it will do it's job for you. 
If you still want to check out, refer to the collab noteboo above.
<br>


  
  

