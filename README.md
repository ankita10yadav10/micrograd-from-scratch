# micrograd-from-scratch
An automatic gradient engine implementing back propagation

# Understanding micrograd — backpropagation from scratch
A learning implementation built while working through Andrej Karpathy's micrograd tutorial.

## What this is
This repo documents my understanding of how autograd engines work by implementing one from scratch. I followed Karpathy's tutorial 
(github.com/karpathy/micrograd) and built the engine step by step, writing notes and experiments alongside the code.

## What I actually understood building this
- How a Value object tracks its own gradient and children
- Why backpropagation is just the chain rule applied recursively on a DAG
- How .backward() knows which order to visit nodes (topological sort)
- How a neural net is just a composition of these tiny operations

## Files
- `building_autograd.ipynb` — my annotated implementation with notes explaining each step in my own words


## Credit
Original micrograd by Andrej Karpathy — MIT License  
https://github.com/karpathy/micrograd  
The YouTube lecture that goes with it:  
https://youtu.be/VMj-3S1tku0
