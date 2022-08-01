# Graded Quiz 1 - Selecting and Training a Model

> **Q1. You are working on a binary classification ML algorithm that detects whether a patient has a specific disease. In your dataset, 98% of the training examples (patients) don’t have the disease, so the dataset is very skewed. Accuracy on both positive and negative classes is important. You read a research paper claiming to have developed a system that achieves 95% on ____ metric. What metric would give you the most confidence they’ve built a useful and non-trivial system? (Select one)**

- [ ] Accuracy 
- [ ] Precision
- [ ] Recall
- [x] F1-score


> **Q2. On the previous problem above with 98% negative examples, if your algorithm is print(“1”) (i.e., it says everyone has the disease). Which of these statements is true?**

- [x] The algorithm achieves 100% recall.
- [ ] The algorithm achieves 100% precision.
- [ ] The algorithm achieves 0% precision.
- [ ] The algorithm achieves 0% recall.
  
> **Q3. True or False? During error analysis, each example should only be assigned one tag. For example, in a speech recognition application you may have the tags: “car noise”, “people noise” and “low bandwidth”. If you encounter an example with both car noise and low bandwidth audio, you should use your judgement to assign just one of these two tags rather than apply both tags.**

- [ ] True
- [x] False


> **Q4. You are building a visual inspection system. Error analysis finds:**

| **Type of defect** 	| **Accuracy** 	| **HLP** 	| **% of data** 	|
|:------------------:	|:------------:	|:-------:	|:-------------:	|
| Scratch            	| 95%          	| 98%     	| 50%           	|
| Discoloration      	| 90%          	| 90%     	| 50%           	|

> **Based on this, what is the more promising type of defect to work on?**

- [ ] Discoloration, because the algorithm’s accuracy is lower and thus there’s more room for improvement.
- [ ] Discoloration, because HLP is lower which suggests this is therefore the harder problem that thus needs more attention.
- [x] Scratch defects, because the gap to HLP is higher and thus there’s more room for improvement. 
- [ ] Work on both classes equally because they are each 50% of the data. 


**Q5. You’re considering applying data augmentation to a phone visual inspection problem. Which of the following statements are true about data augmentation? (Select all that apply)**

- [ ] Data augmentation should distort the input sufficiently to make sure they are hard to classify by humans as well. 
- [ ] Data augmentation should try to generate more examples in the parts of the input space where the algorithm is already doing well and there’s no need for improvement.
- [x] GANs can be used for data augmentation.
- [x] Data augmentation should try to generate more examples in the parts of the input space where you’d like to see improvement in the algorithm’s performance. 



