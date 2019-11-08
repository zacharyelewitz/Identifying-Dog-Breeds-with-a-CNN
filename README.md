# Identifying-Dog-Breeds-with-a-CNN

A friend recently told me about how easy it is to use fast.ai for categorizing pictures so I wanted to try it out for myself. I retrained the ResNet-50 neural network in order to identify a dog picture as either a dalmatian, a dachshund, or a bergamasco shepard. Fast.ai made it fairly straightforward to download the pictures, ensure the pictures weren't corrupted, check for duplicates, and remove irrelevant or poor pictures. Using only 111 images per breed (between both the training and validation sets) I was able to get 100% accuracy when predicting breed on the validation data. 

This project was heavily sourced from the examples in the [fast.ai course](https://course.fast.ai/videos/?lesson=2).
