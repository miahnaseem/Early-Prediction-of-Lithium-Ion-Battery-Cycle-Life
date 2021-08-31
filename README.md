## ABOUT THE PROJECT

Energy production and has the potential to be our main priority as a species in the coming decades. The urgency of the effects of climate change was my main motivation in entering this problem space. The main benefit of these models are in speeding up research and development of better batteries. As battery technology improves, testing the longevity of batteries becomes more time consuming, and so being able to accurately predict the cycle life of a battery before it even shows capacity degradation will speed up R&D tenfold.

## Data

This project builds on prior work, specifically Stanford University's ["Data-driven prediction of battery cycle life before capacity degradation"](https://energy.stanford.edu/sites/g/files/sbiybj9971/f/346501527888d799d94279cfe74049fde53ca2d5a1275d083d28f925253cf657.pdf). They have posted all of their data publicly, which is the largest publicly available battery dataset. The data can be found [here](https://data.matr.io/1/). However, I have processed the data as they did, into three pickle batches. These can be found [here](https://drive.google.com/drive/folders/1wSOeLVcT155gvYFHV8gfF4mpALVP2HsP?usp=sharing). Please add the three batch files to a data folder if you wish to run the project locally.

## Conclusion

In the end, I could not replicate Stanford's results, achieving a MAPE of 9.1% in cycle life prediction. However, I believe with more time to refactor, and more insights into the problem space, I will be able to reach closer to that result. As of now, my model has a MAPE of 35%. However, seeing how the model can gain insights on the battery cycle life within the first 100 cycles (before any capacity degradation), as it stands it is a successful showcase of what can be done. With further research and refactoring, the results will be improved, converting this work into a highly practical model.


