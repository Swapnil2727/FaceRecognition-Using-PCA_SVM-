# FaceRecognition-Using-PCA_SVM-

I am going to discuss a popular technique for face recognition called eigenfaces.
And at the heart of eigenfaces is an unsupervised dimensionality reduction technique called principal component analysis (PCA),
and we will see how we can apply this general technique to our specific task of face recognition.

However, i’ll be using the LFW dataset. 
Luckily, scikit-learn can automatically load our dataset for us in the correct format. We can call a function to load our data. 
If the data aren’t available on disk, scikit-learn will automatically download them for us from the University of Massachusetts’ website.
