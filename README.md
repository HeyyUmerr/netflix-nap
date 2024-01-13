

# Netlify & Nap is a content-based movie recommendation system 
![Screenshot 2024-01-13 150526](https://github.com/HeyyUmerr/netflix-nap/assets/96136178/08e1e129-8340-4951-8661-a3bb9e5ccbb6)

Key points:-
1. Content-based film referral system.
2. The TMDB API is used as a database.
3. Streamlit is utilized in front-end-development and Numpy and Pandas are utilized for Exploratory Data Analysis.


Steps for running the project:-
1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the requirements.txt file with the command pip install -r requirements.txt
3. Get your API key from https://www.themoviedb.org/. (Refer to the below section on how to get the API key)
4. Replace YOUR_API_KEY
5. Run Command:: Streamlit run app.py!
6. Hurray! thats it.


![Screenshot 2024-01-13 151224](https://github.com/HeyyUmerr/netflix-nap/assets/96136178/1ebe2853-84ea-431a-8905-482b69d81d3b)

# How to get the API key?
Create an account at https://www.themoviedb.org/, click on the API link from the left-hand sidebar in your account settings, and fill in all the details to apply for the API key. If you are asked for the website URL, give "NA" if you don't have one. Once your request is approved, you will see the API key in your API sidebar.

![Screenshot 2024-01-13 151047](https://github.com/HeyyUmerr/netflix-nap/assets/96136178/eb16f9a1-209d-4091-8fc0-eae47102871c)
# Note: Due to some subscription issues, the deployed link is not available right now.

# Similarity Score :
How does it decide which item is most similar to the item the user likes? Here are the similarity scores.

It is a numerical value that ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained by measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
# How does Cosine Similarity work?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, the higher the cosine similarity.
![Screenshot 2024-01-13 152304](https://github.com/HeyyUmerr/netflix-nap/assets/96136178/8c746326-2071-46e6-a686-09dc2361a7c5)

# Sources of the datasets
IMDB 5000 Movie Dataset



