# Notes


MSE
R2

| Dataset size (rows) | MSE | R2 |
|-|-|-|
| 1.04M | 50.57 | 0.80 |  
| 600k | 43.19 | 0.83 |
| 300k | 59.48 | 0.78 | 
| 100k | 27.40 | 0.89 | 
| 1k | 42.81 | 0.80 |

I expected the results to get more accurate the more data we throw at the model but that wasn't the case. My explanation for this is that the popularity is also based of the region (different regions tend to prefer different genres/types of music) and since different regions are in different positions in the dataset. 
