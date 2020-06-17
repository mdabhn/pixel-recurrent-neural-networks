# Summary of the paper

    How Generative Modeling works?

    - it helps to genarte new data from INPUT X with LABEL Y. By using the join probability of (X,Y)

---

    Where we use that?

    - we use that in different fields. Like image compression, image classification, image reconstruction etc.

---

    What is autoagressive Rnn model?

    - We predict a pixel by its all previously generated pixels.

---

    Cnn extract information independent of time but Rnn can loop through and can work.

---

    While Rnn is bad for long term depecndency we use LSTM. It adds gates to Rnn so it can have long term memory.

---

[Described Well enough about all the things above](https://towardsdatascience.com/auto-regressive-generative-models-pixelrnn-pixelcnn-32d192911173#:~:text=PixelCNN%20uses%20standard%20convolutional%20layers,that%20preserve%20the%20spatial%20resolution.&text=Then%20feature%20map%20passes%20through,ReLU%20activation%20and%201x1%20convolution.)
