## Compressed Results of [CIFAR-100](https://www.cs.toronto.edu/~kriz/cifar.html)

  |    Network   |     Type    |    Acc (%)    |    FLOPs (M)    |   Params (M)  | Model Size (MB) |
  |:------------:|:-----------:|:-------------:|:---------------:|:-------------:|:---------------:|
  |     VGG19    |   Original  |     72.28     |      796.79     |     20.09     |      80.57      |
  |              | Nota-Simple | 71.13 (-1.15) |  132.20 (6.03x) | 1.17 (17.13x) |  5.00 (16.13x)  |
  |              | Nota-Search | 71.14 (-1.14) |  100.09 (7.96x) | 0.66 (30.38x) |  2.96 (27.23x)  |
  |   ResNet50   |   Original  |     78.03     |     2596.06     |     23.71     |      95.55      |
  |              | Nota-Simple | 76.92 (-1.11) |  613.43 (4.23x) |  2.64 (8.99x) |   11.51 (8.3x)  |
  |              | Nota-Search |  76.63 (-1.4) | 224.70 (11.55x) | 2.17 (10.91x) |  9.54 (10.02x)  |
  | MobileNet V1 |   Original  |     66.68     |      92.90      |      3.31     |      13.59      |
  |              | Nota-Simple | 66.32 (-0.36) |  26.09 (3.56x)  |  0.53 (6.24x) |   2.52 (5.4x)   |
  |              | Nota-Search | 66.11 (-0.57) |  17.90 (5.19x)  |  0.35 (9.35x) |   1.78 (7.66x)  |
