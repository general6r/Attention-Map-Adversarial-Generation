# Attention-map-Adversarial-generation
 
This a very exciting educational project in which you'll see how gradients can be used for a few related tasks, namely to explain which portion of the input the model relied on for making its classification and for creating adversarial examples. In the first part of the project, I explain the method discussed in this paper:

Title: "Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps" (https://arxiv.org/pdf/1803.07728)

The paper shows how we can find the pixels that have the most influence on the model prediction. The same idea can be applied to language models like transformers as well, by computing attention scores for each token (which roughly corresponds to words).

In the second part, we explore the impact of two different adversarial attack on the model prediction, specifically the fast gradient sign method and the iterative gradient sign method. I encourage you to read through these two articles before you start read the code. 

1- Title: "ADVERSARIAL EXAMPLES IN THE PHYSICAL WORLD" (https://arxiv.org/pdf/1607.02533)
2- Title: "EXPLAINING AND HARNESSING ADVERSARIAL EXAMPLES" (https://arxiv.org/pdf/1412.6572)
