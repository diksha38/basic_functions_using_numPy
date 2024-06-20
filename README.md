# basic_functions_using_numpy

Introduction to Python and Numpy

1. Introduction to Python and Numpy
Hello World: Initializes a string variable and prints it to ensure the environment setup is correct.

2. Basic Functions with Numpy
2.1. Sigmoid Function
basic_sigmoid(x): Computes the sigmoid of a real number using math.exp().
sigmoid(x): Vectorized version that computes the sigmoid for a numpy array or a real number using np.exp().
2.2. Sigmoid Gradient

sigmoid_derivative(x): Computes the gradient of the sigmoid function with respect to its input.
3. Reshaping Arrays
image2vector(image): Converts a 3D numpy array (image) into a 2D vector.

4. Normalizing Rows
normalizeRows(x): Normalizes each row of a matrix to have unit length using numpy's broadcasting feature.

5. Softmax Function
softmax(x): Implements the softmax function which normalizes each row of the input matrix.

6. Vectorization
Demonstrates the importance of vectorized operations over classic for-loop implementations to improve computational efficiency. Examples include vectorized dot product, outer product, elementwise multiplication, and general dot product.

7. Loss Functions
7.1. L1 Loss
L1(yhat, y): Computes the L1 loss, which is the sum of the absolute differences between predicted and true values.
7.2. L2 Lss
L2(yhat, y): Computes the L2 loss, which is the sum of the squared differences between the predicted and true labels.
