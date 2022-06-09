# CodeComple: Code Complexity Prediction Dataset
By Seung-Yeob Baik, JoongHyuk Hahn, Mingi Jeon, Sang-Ki Ko and Yo-Sub Han\
Theory of Computation Lab., Yonsei University & Theory of Computation Lab., Kangwon Natinoal University


## Introduction

Our dataset is inspired from the recently revealed AlphaCode. We constructed a dataset with the codes from the coding competition platform Codeforces. The dataset contains 3,817 codes on 7 classes, where each class has around 500 codes each. The 7 classes are constant, linear, quadratic, cubic, $log n$, $n log n$ and NP.

Figure~\ref{fig:workflow} illustrates the process of
the CodeComple dataset generation. For the first procedure we
collect problems and solutions codes from CodeForces. The solution
codes have correct solutions and wrong solutions, and have multiple
programming languages. We filter the correct Java codes as our
statistical population.
Before analyzing the time complexity of each problem, we divide the
problems by the problems solving strategy. This is because it helps
the human annotators to analyze the time complexity, and problems 
with similar solving strategy tend to have similar time complexity.
On the third procedure human annotators inspect the problem and 
solution codes to label each code by their time complexity. Each of
the human annotators have over 5 years of experience on solving
algorithm problems with various programming languages. Each data of
CodeComple dataset comes from algorithm problems and is a algorithm
implementation that solves the corresponding problem. With the
expertise in algorithms and programming languages, human annotators
label each code to its corresponding complexity class.
Algorithm problems have properties that can alter the complexity of
their solution algorihtm implementations.
We, therefore, provide the specific guideline to provides instructions and precautions for labelling the data.
The detailed guideline is demonstrated in Section~\ref{ssec:guideline}.

After the labelling, we use different programming experts to
verify the class of each data that the human annotators assigned.
The verification includes checking the precautions that are included
in the guideline.
The verification is the last procedure of our whole process of generating
CodeComple dataset and we give detailed construction descriptions
in Section~\ref{ssec:details_dataset}.


## Prerequisites


## Download


## Reference


## License
