# DEPI-project
covid-19 x-ray classifier using CNN 
creating CNN classifier for covid-19 chest images x-ray using open source data form kaggle
there are 3 stages for this project 
first we created a model using under sampling to solve the imbalance problem in data and got 96 % accuracy and 97% recall
sccond stage we used under sampling and data augmentation to increase the training data set size and got result almost the same as the first model 
third stage we wantd to use GANs to help increase the covid samples in the data set we used DCGAN to generate Covid images and after 10 days of training on ML on azure we finished 66 epoches and the genrator was able to create almost like the covid images but the loss was not acceptable as the genrator minmum loss was 1.3 and discrimator minmum loss was 0.7 so the GANs need to be trained more to reach a loss that it's acceptable to be used in tarining AI model.. and that's our future goal to improve the DCGAN we created 
