---
dg-publish: true
---

- Retrain all parameters
    its a hard task that need large computations..
- transfer learning 
    in this approach we freeze most of the parameters or layers and then fine tune or "retrain" the head layers "last few layers" to give us the target
- parameter efficient fine-tuneing
    here we are freezing all the parameters, and instead we are adding new pretrained parameters --> that can done by low Rank-adaptation
