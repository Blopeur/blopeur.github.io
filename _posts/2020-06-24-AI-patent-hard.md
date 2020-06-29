---
layout: post
published: true
main: true
title: "AI Patenting Pitfalls"
description: "It is not sufficient for an AI patent claims to contains a causal link to a technical purpose for the application to be successful."

picture: aipitfall.jpg

label_default: "patent" 
label_primary: "Artificial Intelligence"
label_info: "Claims"
---
<!-- Main Container -->
AI application claims can be patentable if underlying algorithm or computation model “contains a causal link to a technical purpose.”
By Example : “using neural network in heart monitoring apparatus to ID irregular heartbeats.”

However, this is not just enough to get your idea patented as demonstrate a recent [EPO ruling](https://www.epo.org/law-practice/case-law-appeals/pdf/t180161du1.pdf)
The application was for a method of determining cardiac output from blood pressure using an artificial neural network with learning-determined weight values.
The neural network was used to transform the measured radial blood pressure into equivalent aortic pressure, from which cardiac output was calculated.

The reviewer notes that the application gives very little information about the data used for learning the neural network, merely stating that the input data should cover a wide range of patients in terms of age, sex, health status, constitution, etc.
And, without disclosing which data are suitable for network learning, the skilled person cannot rework the learning and thus implement the invention.

The EOP concludes that the invention disclosure does not contain enough information, and as a result, prevent the replication of the invention. More specifically, it is not possible to recreate the artificial neural network due to the lack of information regarding the input data and training operations. 
 To avoid such a scenario, we would remind you 
to make sure that any AI / Machine learning patent claims contains the following information : 

    * Input data preparation
    * Model structure, modification
    * Training phase process
    * Output data post-processing
    * AI/ML-based hardware and/or architecture

All the above should be addressed separately in the claims. Last but not least, you should also understand that the output of data alone is not patentable. 
For a successful application, it needs to describe the entire AI system, including use of output. 
Your application should also contain a description of :

    * Data training phase, model structure, placement of model in a more extensive system, output to perform XXX
    * Pre-processing of training data
    * Used of trained classifiers, the sequence of classifier use
    * End to end workflow description
    * Hardware that provides input to / receives and uses the output of AI systems
    

<!--End Main Container -->
