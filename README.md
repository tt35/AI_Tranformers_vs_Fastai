# Project Description

Image classification has been a popular field of AI applications. For example, an image
classification model can tell if the picture given is whether a dog or a cat. In CS 344 - Artificial Intelligence at Calvin University, the main library we
used to do the task was [Fast.ai](https://www.fast.ai/), which is a deep learning tool. In the class, we also used [Transformers](https://huggingface.co/docs/transformers/index). It is  library that are often used for natural language processing, such as text summarization and sentiment
analysis. 

However, recently, they extend the application of Transformers to image classification task as
well. uring the conversation with the course instructor, he mentioned that he is planning to use
Transformers for image classification eventually, which gave me the idea for my final project. 

In this project, I redid one of the homework where we used Fast.ai library to implement image classification, but
this time, I used Transformers instead. After creating the model, I compared the model’s accuracy and
implementation easiness.

![image](https://user-images.githubusercontent.com/58647594/172662664-26c040a7-15db-41c4-baea-ce9cb4cfb38d.png)


The results were shown above. I tested 4 times, and in each test, I calculated accuracy.
Accuracy measures the percentage of the right answers out of the total cases. As the pictures show,
Transformers model has much better accuracy that the Fast.ai model. The range of accuracy for
Transformers is 0.88 to 1.0, which it is 0.74 to 0.94. It is also impressive that the Transformers model had
accuracy of 1.0 three times. However, one thing that I noticed was that it takes a lot more coding to
implement Transformers model compared to Fast.ai model. In Fast.ai, there are functions that do all the
tedious setting for you while Transformers do not.
