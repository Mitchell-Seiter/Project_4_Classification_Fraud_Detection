Dear Rocky Mountain Town Bank President,

Hope all is well. I wanted to reach out to you with the progress that has been made thus far. 

I have been looking at the data that you sent over and have cleaned it up a bit. I got rid of quite a few of the columns while also adding a couple that I thought might be useful, such as distance from merchant. I did some exploratory data analysis and found that out of the 1000 customers in the data set, only about 200 of them were responsible for all of the fraud. I am hoping to include this in my model building later, but have not done so yet. 

What I have been able to do is build a couple different models so far, including a KNN and logistic regression model. Because the fraudulent transactions only comprise about 1/2 of a percent of the total transactions I was not able to get anything too useful from the KNN model, but have been able to get a little bit from the logistic regression model. 

Below I have included a couple charts of how the logistic model is performing so far: 

Figure One: 

<img src="https://i.imgur.com/dmZKQra.png" alt="drawing" width="400"/>


Figure Two: 

<img src="https://i.imgur.com/opCpTAC.png" alt="drawing" width="400"/>

In figure two you can see a confusion matrix that is at a probability threshold of 0.004. At this threshold we are able to catch about 8% of fraud cases while also catching about 95% of actual transactions. 

I am hoping to greatly improve on this model by starting to give more weight to the fraud transactions rather than having everything be weighted equally. I also want to try some random forest models as well to see if that model can give better predictions. 

But all in all I am on the right track to having a more robust fraud detection model being built and look forward to presenting my findings on Friday. 

If you have any questions or concerns please do not hesitate to reach out. 

Kind regards,

Mitchell 





