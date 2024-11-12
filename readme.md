# Vector Dot Product Algorithm

This project implements the **Vector Dot Product** algorithm in Python. Below is the mathematical expression, example code of the algorithm.

## Mathematical Expression

The dot product of two vectors **A** and **B** is calculated as:

$$
\text{Dot Product} = A \cdot B = \sum_{i=1}^{n} A_i \cdot B_i
$$

Where:
- $A_i$ is the i-th element of vector **A**
- $B_i$ is the i-th element of vector **B**

## Example Code

```python
def dot_product(A, B):
    return sum(a * b for a, b in zip(A, B))

A = [1, 2, 3]
B = [4, 5, 6]
result = dot_product(A, B)
print(f"Dot product: {result}")

