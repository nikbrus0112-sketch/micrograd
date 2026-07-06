# micrograd

A tiny autograd engine built from scratch, following Andrej Karpathy's 
"Neural Networks: Zero to Hero" series.

## What this is

A minimal implementation of reverse-mode automatic differentiation (backpropagation) 
and a small neural network library built on top of it. Supports scalar-valued 
autograd — building a computational graph and backpropagating gradients through 
basic operations (add, multiply, tanh, etc.).

## What I learned

- How backpropagation actually works under the hood, not just as a library call
- How computational graphs track operations for the backward pass
- Learned how neural networks are structured and how individual pieces of them are built

## Contents

- `micrograd.ipynb` — the full implementation and walkthrough

## Credit

Built following [Karpathy's Zero to Hero series](https://www.youtube.com/watch?v=VMj-3S1tku0).