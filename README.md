# Incident-Resolution-Prediction-for-IT-Support <br>
In the IT Support industry all the company uses some form of ITSM tool and depending upon this tool, it draws contract with the client.<br>
In the Outsourcing world, the Outsourced company draws profit, gives penalty and measures performance majourly based on this.<br>
Therefore this ITSM tool has most/all the information about the company's IT details.<br>
Hence the Incident details like Description and Subject, was not part of this dataset as it is sensitive data.<br>
However upon analysis we could find that even without the details of the Incident we were able to make a meaningful prediction on the estimated resolution time.<br>
As the IT Support Industry is driven by SLA, instead of poaching it as a Regression I posed it as a Classification problem. Binning the Days to resolution in small buckets.<br>
I found that KNN is able to perform the best of all the Classification techniques used and with an F1 score of above 0.85. However the MultiLayerPerceptron was able to outperform KNN with an F1 Score of above 0.91.<br>
I believe if I get the Issue details then the Model will perform even better.<br>
