Here is my understanding so far:
- There is only one loss component which is the arc face loss
- This is not a "contrastive" approach, but a "discriminative" approach. Thus having more classes and having more images in each classes would increase the performance.
- I was confused by taking the similarity between the weights and the features. Now, I understand that:
    1. Multiplying features by weights represent the cosine similarity operation
    2. During training we are encouraging the embeddings to be more unique and weights to be the "class center" 
- The margin is to keep the clusters more compact
- In addition to angular margin, the cross entropy function promotes the inter-class separation.
Please evaluate each one and make correction if needed.