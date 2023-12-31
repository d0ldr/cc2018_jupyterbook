---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Inlamning 1: Moln till Pico.
1) Koppla upp Raspberry Pico
2) Skicka data över internet!

```{code-cell} ipython3
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(0,3.14,50)
y = np.sin(x)

plt.plot(x,y)
plt.show()
```

Vem vill ha en korv?