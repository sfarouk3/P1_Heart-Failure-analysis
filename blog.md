# Heart Failures Analysis

![intro_image](https://github.com/sfarouk3/P1_Heart-Failure-analysis/blob/main/Uda_P1_pic/heart%20(2).png)


### Table of Contents

1. [Overview](#Overview)
2. [Business Understanding](#BusinessUnderstanding)
3. [Analysis & Findings](#Findings)
5. [Conclusion](#Conclusion)

## Overview <a name="Overview"></a>

In this blog i'll analyse the heart failure reasons and the relation between them

So let's get started.

## Business Understanding <a name="BusinessUnderstanding"></a>

My objective of this analysis is to answer the following questions:

- Q1-What's the Correlation between heart failure and different aspects?
- Q2-What is the smokers' percentage for each gender?
- Q3-Can the frequency of follow up times affect the death events?


In the next section you can find analysis and answers for each of the above questions.


## Analysis & Findings <a name="Findings"></a>

#### *Q1- What's the Correlation between heart failure and different aspects?

To answer my first question let's have a look at the data

![figure_1](https://github.com/sfarouk3/P1_Heart-Failure-analysis/blob/main/Uda_P1_pic/describe.png)

let's also confirm that we don't have any missing data, as we can see there're no missing data in the dataset.

![figure_2](https://github.com/sfarouk3/P1_Heart-Failure-analysis/blob/main/Uda_P1_pic/null.png)

Now, let's see the correlation between different aspects in the dataset, as we can see from  below matrix we can see positive correlation between sex and smoking and negative correlation between time and Death events

![figure_3](https://github.com/sfarouk3/P1_Heart-Failure-analysis/blob/main/Uda_P1_pic/corr.png)


#### *Q2-What is the smokers' percentage for each gender?

we can notice that males has higher smokers percentage than femails and that's matching the high positive correlation between sex and smoking

![figure_4](https://github.com/sfarouk3/P1_Heart-Failure-analysis/blob/main/Uda_P1_pic/smoking%20per%20Gender.png)

#### *Q3-Can the frequency of follow up times affect the death events?

We can notice that the higher the times of follow up the lower the death events and  that's match ing the high negative correlation between Time and Death_Events

![figure_5](https://github.com/sfarouk3/P1_Heart-Failure-analysis/blob/main/Uda_P1_pic/Death%20Events_times.png)

## Conclusion <a name="Conclusion"></a>

Now let's summarize the findings:

- Males tends to be smokers more than females
- The higher the times of follow up the lower the death events
