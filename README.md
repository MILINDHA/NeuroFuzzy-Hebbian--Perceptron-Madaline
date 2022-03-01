# NeuroFuzzy-Hebbian--Perceptron-Madaline

# -- Hebbian --
## Python implementation of Hebbian Learning on AND
## Step 0 :  Initialize all weights:
   wi = 0 (i = 1 to n).
## Step 1: For each input training vector and target output pair, s:t, do steps 2-4.
    
## Step 2: Set activations for input units:
   xi = Si (i = 1 to n)
## Step 3 : Set activation for output unit:
   y = t
## Step 4: Adjust the weights for xi
  wi(new) = wi(old) + xiy (i = 1 to n)
    
   Adjust the bias:
        b(new) = b(old) + y
