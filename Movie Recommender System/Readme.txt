Boltzmann Machine
- It is like you allow a litre of gas in a huge room. Initially its all densely in the place of release. At equilibrium it distrubutes all around the room so as to attain minimum energy state . This explains the working of boltzmann machine.
- Restricted Boltzmann Machines(RBM) are shallow, two-layer neural nets that constitute the building blocks of deep-belief networks. The first layer of the RBM is called the visible, or input layer, and the second is the hidden layer. 
- In this project, RBM predicts whether a person will like the movie or not.
- RBM is implimented using pytorch from scratch. 
AutoEncoder
- Hey neural network what if your output is again your input! Would you try to see the patterns....yeah you will!! So auto encoders are nothing but ANNs with same input and output. Rather than terming this unsupervised one can say it is Self Supervised Learning.
- Here, I used stacked autoencoders(SAE) to predict ratings of movies from 1-5 and recommend it to people.
- SAE network is also implimented using pytorch from scratch.