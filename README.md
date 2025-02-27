# hilbert-space-llm
Silly idea for a hilbert space formulation of neural networks, where embeddings exist in L^2 function space.

Prompted Deep Research to research and evaluate this idea.

### Notes

Obviously the truncated basis representation effectively just turns it into a classic discrete transformer. FNet is very close to what I'm envisioning I think. Basically what I'm thinking here is, the same difference between mp3 and wav formats. Suppose we store the embedding and weights as, basically, coefficients to sin functions (e.g. doing the processing, inference, training *in* frequency space on these coefficients). I'm curious what the math would change into, what benefits or drawbacks we might get (the deep research response answered a lot of these questions but I still have a lot). 


### Update

cool paper with similar ideas: https://x.com/omarsar0/status/1894757821587296614 https://arxiv.org/abs/2502.18394
