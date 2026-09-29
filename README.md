# Mon premier projet

Calcul de la moyenne de valeurs dans un vecteur
$$\bar{x} = \frac{1}{n} \sum_{i=0}^n x_i$$

## compilation 

```
mpic++ --std=c++17 -o mean mean.cpp
```

## sous codespace

il faut installer openmpi

```
sudo apt update
sudo apt install libopenmpi-dev openmpi-bin
```