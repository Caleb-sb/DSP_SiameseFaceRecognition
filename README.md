# Facial Recognition with MobileNet
The repo contains the following for EEE4114F (Digital Signal Processing):
- A trained model to be used in a Siamese structure based on a slightly altered MobileNetV1 structure
- The colab Notebook used to create, train and test the model with a custom loading function for Triplet Learning
- The report submitted on the project

### A note on the face database
A substandard database was used to train this database with subjects using the same clothes and hairstyles which might have   positively skewed test results. Ideally, during both testing and training the pictures used would consist of different   outfits and hairstyles and be shot under a multitude of lighting conditions. (Although Jitter was added to the training   images to attempt to address the lighting)
