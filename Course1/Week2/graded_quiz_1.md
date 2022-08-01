# Graded Quiz 1 - Selecting and Training a Model

> **Q1. Which of these is a more accurate description of a data-centric approach to ML development?**

- [ ] Holding the training data fixed, work to improve your neural network’s architecture to do well on the problem.
- [x] Holding the neural network architecture fixed, work to improve the data to do well on the problem.


> **Q2. Say you have an algorithm that diagnoses illnesses from medical X-rays, and achieves high average test set accuracy. What can you now say with high confidence about this algorithm? Check all that apply.**

- [ ] It does well even on rare classes of diseases. 
- [ ] Its diagnoses are roughly equally accurate on all genders and ethnicities, so we are confident it is not biased against any gender or ethnicity.
- [ ] The system can be safely deployed in a healthcare setting. 
- [x] None of the above.
  
> **Q3. Which of these statements about establishing a baseline are accurate? Check all that apply.**

- [ ] Open-source software should not be used to establish a baseline, since the performance of a good open source implementation might be too good and thus too hard to beat. 
- [x] It can be established based on an older ML system. 
- [x] For unstructured data problems, using human-level performance as the baseline can give an estimate of the irreducible error/Bayes error and what performance is reasonable to achieve. 
- [x] Human level performance (HLP) is generally more effective for establishing a baseline on unstructured data problems (such as images and audio) than structured data problems.

> **Q4. On a speech recognition problem, say you run the sanity-check test of trying to overfit a single training example. You pick a clearly articulated clip of someone saying “Today’s weather”, and the algorithm fails to fit even this single audio clip, and outputs “______”. What should you do?**

- [x] Debug the code/algorithm/hyperparameters to make it pass this sanity-check test first, before moving to larger datasets.
- [ ] Use data augmentation on this one audio clip to make sure the algorithm hears a variety of examples of “today’s weather” to fit this phrase better.
- [ ] Create a training set of this example repeated 100 times to force the algorithm to learn to fit this example well.
- [ ] Train the algorithm on a larger dataset to help it to fit the data better.







