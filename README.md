# Code for IU Deep Learning (DLDMSDL01) presentation on topic: Generalization Ability of Deep Learning Models

In this repository you can find the complete code to replicate the examples in my presentation for the course DLDMSDL01 at International University. The example is motivated by the toy example taken from

Geirhos, R., Jacobsen, J.-H., Michaelis, C., Zemel, R., Brendel, W., Bethge, M., & Wichmann, F. A. (2020). Shortcut Learning in Deep Neural Networks. ArXiv:2004.07780 [Cs, q-Bio]. http://arxiv.org/abs/2004.07780

(https://github.com/rgeirhos/shortcut-perspective)

### Motivational example:

**Biased training data and i.i.d. test data**
Cats are either shown in top left or bottom right quadrant of image and cows are either shown in top right or bottom left quadrant of image.

![ ](./images/cow_vs_cat_biased.png  "biased data")

**Unbiased o.o.d. test data**
Cats and cows can be shown at random positions on the image.

![](./images/cow_vs_cat_unbiased.png "unbiased data")