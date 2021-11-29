# BoneAgeDetection
Semester Project

##### Dataset is taken from the following site
https://www.rsna.org/education/ai-resources-and-training/ai-image-challenge/rsna-pediatric-bone-age-challenge-2017
##### It contains pediatric hand radiographs
###### Skeletal growth of children are often assessed by calculating bone age. This age is different from chronological age, calculated from date of birth. Bone age is used by pediatrician to detect growth disorders. It is often used in medico legal cases where actual age of individual is not known. Bone age detection of unknown people is one of the important point in clinical procedure of estimating the biological maturity of children. It can be done by comparing hand X-rays with known X-ray samples. Manual methods of evaluating bone age are cumbersome and time consuming, so the aim is to generate an automated method to evaluate the age. Various approaches are done to achieve this and many are still in progress. The company16bit.ai  has developed a software which predicts the age of bone from hand radiograph with standard deviation of 9 months, our goal is to reduce this std deviation to 4 months using segmentation approach. We are using a segmentation mask of phalanges, carples, metacarples, and radius ulna to train a convolutional UNET to predict segmentation mask for the dataset and successfully segmented phalanges from the hand X-rays for the test data.
##### The model is trained on 160 images.
##### The project is still in progress...
