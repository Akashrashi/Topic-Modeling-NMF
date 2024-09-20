# Topic_Modeling_NMF
Topic modeling is a technique to extract relevant topics and themes from the collection of documents. One of the way to perform topic modeling is via Non-Negative matrix factorization (NMF).  
NMF factorizes a non-negative matrix 𝑉of dimensions 𝑛 × 𝑚 into two non-negative  matrices, 𝑊 (𝑛 × 𝑘) and 𝐻(𝑘 × 𝑚) such that,
<div align="center">
  <img src="https://latex.codecogs.com/svg.latex?\color{white}\min_{W,H}||V-WH||" />
</div>
where|| ⋅ ||𝐹  represents the Frobenius norm, and the aim is to minimize it.  
Based on different cost functions (𝛽_𝑙𝑜𝑠𝑠) we have different factorization methods.  
 
## Syntax (Scikit-learn implementation)
**NMF** (n_components = 'warn', init = None, solver = 'cd', beta_loss = 'frobenius', tol = 0.0001,
max_iter = 200, random_state = None, alpha_W = 0.0, alpha_H = 'same', l1_ratio = 0.0, 
verbose = 0, shuffle = False)
