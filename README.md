# digitReconizer
This is a machine learning model made to recongize images of handwritten numbers in a 28x28 pixel frame, orignary from a Kaggle competition
https://www.kaggle.com/competitions/digit-recognizer/overview, the data The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.

Each pixel column in the training set has a name like pixelx, where x is an integer between 0 and 783, inclusive. To locate this pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27, inclusive. Then pixelx is located on row i and column j of a 28 x 28 matrix, (indexing by zero).

The data was obtained from  MNIST ("Modified National Institute of Standards and Technology") which is the de facto “hello world” dataset of computer vision.
To run the code first unzip the data iun the data folder.
You can find the libraries and its version in the requirements.txt
