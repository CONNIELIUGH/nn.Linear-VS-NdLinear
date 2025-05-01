# nn.Linear-VS-NdLinear

I created this .ipynb notebook to highlight the differences between PyTorch's nn.Linear and NdLinear by Ensemble AI.

Conclusion:

- NdLinear offers more flexibility, as it can apply transformations across multiple dimensions; nn.Linear is limited to transforming only the last dimension of the input tensor.

- NdLinear updates parameters for each dimension independently which preserves the potential relationships between dimensions. In contrast, nn.Linear flattens the input into a 2D matrix, which can destroy important dimensional relationships, result in more parameters, and potentially decrease accuracy.



## Overall, NdLinear is more useful when working with higher-dimensional data because it preserves structural relationships between dimensions. I am looking forward to applying NdLinear in future projects!
