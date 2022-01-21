# Learning to sense from events via semantic variational autoencoder

- Marcos Gôlo (ICMC/USP) | marcosgolo@usp.br
- Rafael Rossi (UFMS) | rafael.g.rossi@ufms.br
- Ricardo Marcacini (ICMC/USP) | ricardo.marcacini@icmc.usp.br

# Abstract
In this paper, we introduce the concept of learning to sense, which aims to emulate a complex characteristic of human reasoning: the ability to monitor and understand a set of interdependent events for decision-making processes. Event datasets are composed of textual data and spatio-temporal features that determine where and when a given phenomenon occurred. In learning to sense, related events are mapped closely to each other in a semantic vector space, thereby identifying that they contain similar contextual meaning. However, learning a semantic vector space that satisfies both textual similarities and spatio-temporal constraints is a crucial challenge for event analysis and sensing. This paper investigates a Semantic Variational Autoencoder (SVAE) to fine-tune pre-trained embeddings according to both textual and spatio-temporal events of the class of interest. Experiments involving more than one hundred sensors show that our SVAE outperforms a competitive one-class classification baseline. Moreover, our proposal provides desirable learning requirements to sense scenarios, such as visualization of the sensor decision function and heat maps with the sensor's geographic impact. 

# Proposal: SVAE + One-Class Sensing
![Proposal](/images/TVAE.png)

# Results
![Results](/images/results.png)



