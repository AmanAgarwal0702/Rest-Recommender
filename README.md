## Restaurant Recommender ( CS-F407 Artificial Intelligence Lab Project )
## Submitted to Dr. Aneesh Chivukula

>Group details

Aman Agarwal   : 2020B4AA2328H  
Gauri Tewari   : 2020B4A32314H    
Kartik CHitoor : 2020B4A81617H

The project makes use of Machine Learning techniques to recommend 10 restaurants to a user living in Hyderabad, India based on the input.
It takes input from the user for the following attributes:

> Restaurant Type ( Casual Dining, Cafe, Quick Bites etc.)
> Cuisines (North Indian, Italian, Continental etc.)
> Approximat Cost for two people (Cheap, Affordable, Expensive etc.)
> Location (Multiple locations of Hyderabad like Jubille Hills, BITS Hyderabad, Secunderabad etc.)

It then applies TF-IDF (Term Frequency-Inverse Document Frequency) and Cosine Similarity to find similarity scores for all the restaurants
present in the dataset i.e. 51,717 spread across the city of Hyderabad.

Then the output is given in the form of top 10 restaurants with multiple other fields like
>Address
>Online order available
>Rating (out of 5)
>Dishes liked
