# SVM-Analysis
Support Vector Machine (SVMs) is one of the most powerful algorithms for problem solving in machine learning and is known to have deep roots in the fields of Statistical Learning Theory (SLT) and optimization problems along with numerous industrial applications. SVMs are known to reduce most of the problems in machine learning to optimization problems and the latter lies at the heart of SVMs. Due to its higher accuracy, support vector machine is a widely researched topic in the machine learning community. The algorithm promises a higher empirical performance. This project illustrates a detailed understanding of Support Vector Machines along with different parameters associated along with it. Besides, the project presents a comparative analysis of different SVM kernels on the ‘Gender Recognition using voice’ dataset. The accuracy scores were listed and displayed before and after hyperparameter tuning along with the overall percentage increase in the scores after performing tuning.

SVM use supervised algorithms using support vector classifier as a base. The term support vector classifier is derived from the fact that all the observations on the edge and within the soft margins are called support vectors. It is one of the most important algorithms which are applicable for both classification as well as regression datasets. However, normally it is used for classification problems. The algorithm was first introduced in 1960 but it was Vapnik and his coworkers by the early 90s. This algorithm is extremely effective as it could handle numerous categorical and continuous variables.

Apart from machine learning, SVMs are also known to be effective in the domain of data mining. Numerous studies highlight the fact that SVMs are known to have significantly higher amount of accuracy as compared to other existing traditional classification algorithms. It is largely because they proceed with problem solving using finite training points and thus do not face the problems like overfitting, curse of dimensionality etc. It maps the training data in space to increase the separation between the categories. The newer data points would be mapped in the same space and would be predicted and placed in a category. 

SVM supports both linear and non-linear classification. The latter is carried out by using kernel trick which simply means mapping the inputs in non-linear data into a higher-dimensional feature space.

The success of SVMs is mainly attributed to three fundamental reasons: Kernel trick, principle of maximal margin and dual theory. However, for some of the datasets, the values of cost and kernel parameters play a significant role in the accuracy of the model. Therefore, the user needs to continually perform considerable cross validation to obtain optimum parameter settings which in turn would result a higher accuracy score.  Kernels are referred to as a core of SVM since they support a set of mathematical functions which are used for manipulation of data. In terms of real-time applications, SVMs are used in medical decision support, face authentication, image recognition, text categorization etc. SVMs are also applicable for all kinds of datasets be it, audio, video or text.


## About the dataset
This database was created to identify a voice as male or female, based upon acoustic properties of the voice and speech. The dataset consists of 3,168 recorded voice samples, collected from male and female speakers. The voice samples are pre-processed by acoustic analysis in R using the seewave and tuneR packages, with an analyzed frequency range of 0hz-280hz (human vocal range).

The following acoustic properties of each voice are measured and included within the CSV:

meanfreq: mean frequency (in kHz)<br />
sd: standard deviation of frequency<br />
median: median frequency (in kHz)<br />
Q25: first quantile (in kHz)<br />
Q75: third quantile (in kHz)<br />
IQR: interquantile range (in kHz)<br />
skew: skewness (see note in specprop description)<br />
kurt: kurtosis (see note in specprop description)<br />
sp.ent: spectral entropy<br />
sfm: spectral flatness<br />
mode: mode frequency<br />
centroid: frequency centroid (see specprop)<br />
peakf: peak frequency (frequency with highest energy)<br />
meanfun: average of fundamental frequency measured across acoustic signal<br />
minfun: minimum fundamental frequency measured across acoustic signal<br />
maxfun: maximum fundamental frequency measured across acoustic signal<br />
meandom: average of dominant frequency measured across acoustic signal<br />
mindom: minimum of dominant frequency measured across acoustic signal<br />
maxdom: maximum of dominant frequency measured across acoustic signal<br />
dfrange: range of dominant frequency measured across acoustic signal<br />
modindx: modulation index. Calculated as the accumulated absolute difference between adjacent measurements of fundamental frequencies divided by the frequency range<br />
label: male or female<br />

Link for dataset: https://www.kaggle.com/primaryobjects/voicegender
