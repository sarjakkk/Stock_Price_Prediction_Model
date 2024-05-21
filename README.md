# Google Stock Price Prediction

This project involves the use of Recurrent Neural Networks along with Long Short-Term Memory (LSTM) to
predict the stock prices of Google.

## About RNN
Recurrent Neural Network (RNN) was designed, like any other Neural Network, to function like a specific part
of the human brain. When looking at our brain’s cerebrum, we can divide it into the Temporal, Parietal,
Occipital and Frontal lobe. Out of these, the Frontal lobe is the part which deals with short-term memory and
remembers what happened in the immediate present and use it for decision making in the near future. It is
this Frontal lobe that the RNN tries to replicate.

## About LSTM
The Long Short-Term Memory (LSTM) is a variation of the RNN which solves the Vanishing Gradient Problem,
which leads to the decrease in gradient for each level in a regular RNN because of the Recurring Weight being
close to 0. This leads to a difficulty in the manipulation of weights for a layer farther away from the present
layer and thus makes predictions inaccurate. We would not go into the details of this phenomenon.