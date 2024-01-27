# Which-Bollywood-Celebrity-Are-You
Model detects which celebrity looks like you

1. We have used VGG-Face for feature extraction.
2. We have total 8000 bollywood actor/actress images .
3. I have reduced the dimensions to 224 x 244 as it is a requirement for VGG-Face.
4. VGG-Face generates 2048 features for each image , which gives us a vector of 8000 x 2048 dimension
5. For prediction , we will follow same process for a single uploaded photo 1 x 2048 dimension
6. I have used cosine similarity to find the distance between the vectors.
7. Then the model compares the uploaded photo vector with our train data vector.
8. Least distance gives us maximum similarity.








