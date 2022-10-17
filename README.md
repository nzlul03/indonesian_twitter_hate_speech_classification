# Indonesian Twitter Hate Speech Classification

## Dataset
The Dataset for Hate Speech Detection in Indonesian (https://github.com/ialfina/id-hatespeech-detection).

### Data Format
The dataset consists of two data columns : label - tweet. It consists of 713 tweets in Indonesian.
The labels:
- Non_HS for "non-hate-speech" tweet (453).
- HS for "hate-speech" tweet (260).

### Exploratory Data Analysis
The label distribution:\
![image](https://user-images.githubusercontent.com/54148951/196093666-76586d09-1400-4522-a68b-b11716748ceb.png)

Histogram : The distribution of "the text data length".
![image](https://user-images.githubusercontent.com/54148951/196093453-d2f81067-7430-4e0b-a3e9-98b536cfedc2.png)

### Data Preprocessing
Since the dataset is unbalanced, we do over-sampling to create a balanced dataset.


## References
Ika Alfina, Rio Mulia, Mohamad Ivan Fanany, and Yudo Ekanata, [_"Hate Speech Detection in Indonesian Language: A Dataset and Preliminary Study
"_](https://ieeexplore.ieee.org/abstract/document/8355039), in Proceeding of 9th International Conference on Advanced Computer Science and Information Systems 2017(ICACSIS 2017).
