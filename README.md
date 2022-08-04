# Neural Network from Scratch

2 layer neural network using only numpy (no tf/keras)



## Usage/Examples

```py
_, _, _, a2 = forward_prop(w1, b1, w2, b2, x_test)
pred = get_pred(a2)

acc = get_acc(pred, y_test)

print("Test Accuracy: ", acc)
```

The model achieves an accuracy of 88% on test data
## Dataset

trained and tested on the mnist dataset of handwritten digits
