---
title: First Post
date: 2022-12-17 22:03:00 +0800
categories: [Blog]
tags: [misc]     # TAG names should always be lowercase

toc: true
math: true
---


# Code

Code block testingsssss

```python

import numpy as np

def f(x):
    return 1 / (1 - 0.5 * (np.sin(x))**2)

N = 100000
result = 0.0

for i in range(N):
    rand_x = np.random.uniform(0,1)
    result += f(rand_x)

final_result = result / N 
print(final_result)

```

# Math
In this question, I have refer to the Monte Carlo integration on Wikipedia. We have the general approximation equation:
$$
V \langle f \rangle =  V\frac{1}{N}\sum_{i=1}^{N}f(x_i) \\
V  =  \int_{\Omega }^{} dx
$$


The $\Omega$ in this question, is the uniform distribution variable from 0 to 1.
So we have $V = \int_{0}^{1} dx = 1$ The above equation  will be 
$$
V \langle f \rangle =  \frac{1}{N}\sum_{i=1}^{N}f(x_i)
$$



# Prompts

> Example line for prompt.
{: .prompt-info }


