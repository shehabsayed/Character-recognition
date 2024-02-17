# Character-recognition
• Problem description: The data given are flattened pixels of images of the Arabic letters. The task is to implement a 
model that accurately tells what character the pixels form.
• Problem solution: The data is preprocessed with normalization, scaling pixel values between 0 and 1 by dividing 
each pixel by 255. Then, the code tests four models: two neural networks, support vector machine (SVM), and knearest neighbors classifier (KNN). Each model calculates accuracy and F1 score, plots a confusion matrix, displays 
the first ten images, and prints true and predicted labels for each. Finally, the code compares test accuracies of all 
models and prints the best model's name and accuracy.
