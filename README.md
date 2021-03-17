# Document Recommendation using Vector Space Model

A Document Recommendation Program built in Python.<br><br>
This program recommends the most appropriate Recipe from the collection of Recipe documents according to the Query (input) of the user.<br>

The program follows the following steps:<br>

> -  Preprocessing all the input documents from the document collection, and producing valid tokens.
> - Representing every token from the documents as a vector in the Vector Space Model.
> - Calculating the df (Document Frequency) and TF-IDF (Term Frequency — Inverse Document Frequency) for every token.
> - Calculating the length of Document Vectors for calcluating the Cosine Similarity
<br>

> - Preprocessing the Query Document, which is the input from the user, and finding the most relevant tokens.
> - Calculating TF-IDF of these tokens and representing these tokens as vectors.
> - Applying Cosine Similarity on the Query tokens and the Document Tokens to find the most relevant document.

The most relevant document is then displayed to the user, along with the names of all matching documents.


Sample Input:

```
Recipies containing milk
```

Output:
```
Cosine similarities of the Query document with the given documents are: 

 {'DOC1': 0.0935500990115709, 'DOC2': 0.0, 'DOC3': 0.0, 'DOC4': 0.0, 'DOC5': 0.0, 'DOC6': 0.0, 'DOC7': 0.0, 'DOC8': 0.10908954076547449, 'DOC9': 0.0, 'DOC10': 0.0}


The reccomended documents are: ['DOC1', 'DOC8']


Displaying the most relevent document i.e  DOC8

 Espresso Coffee Recipe

Awaken your senses every morning with a refreshing cup of Espresso coffee and kick start your day on a healthy note. Easy to prepare at home, this beverage will surely be a favorite of everyone at your house. You can have this refreshing cup of coffee at anytime of the day with some exotic cookies for better taste. The aroma of this amazing non-alcoholic beverage will surely win hearts of people around you.

Read less
Ingredients of Espresso Coffee
3 cup milk
2 teaspoon coffee powder
chocolate syrup as required
1/2 cup water
sugar as required
1/4 teaspoon drinking chocolate
How to make Espresso Coffee

Step 1
Add milk to a bowl and boil it on a medium flame.

Step 2
Add water, coffee powder and sugar to the blender jar and grind until it forms a foamy liquid.

Step 3
Add the coffee-water mix to it when the milk starts boiling and rising upwards .

Step 4
Simmer it for a minute and when the boil comes again, remove from the flame. Your frothy espresso coffee is ready.

Step 5
Pour into the coffee mugs and sprinkle some chocolate powder.

```
