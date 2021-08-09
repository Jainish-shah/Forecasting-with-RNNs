# Forecasting-with-RNNs

`Recurrent Layer` at each time step the memory cell takes a `n` by 1 matrix as input, along with state matrix. In simple RNN, a memory cell is regular dense layer and state matrix is the copy of the output matrix.

RNN requires 3D inputs, batchesize, number of time steps & dimensionality of input.
- Recurrent layers use hyperbolic tangent activation function as it outputs the values between -1 and 1.
