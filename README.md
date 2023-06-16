# Machine-Learning

We are using a transfer learning as machine learning technique that used in this project. We decide to use VGG16 architecture to detect pollutant PM2.5 from an image captured by camera. We decide to use VGG16 because there is a research about similar problem with ours. 

For the IDE we used google colaboratory. Although the  data is not that big. We almost used all the free resource provided by google colab and sometimes it caused to crash itself because out of memory. For the notebook you can access it from the link.

Because PM2.5 has numeric datatype, we use RMSE and R-square for the metric. The result we reach 92% of R-square which is could be interpreted that the model can explain 92% of the variation in the response variable arounds its mean. But for some reason we got 31.84 as RMSE.
After we got the value of PM2.5, we label it to 6 catagorize from good to severe. After comparing its predict category and its real category we have 80% of accuracy at best. 
For improvement we would like to gather dataset because the dataset that we used is skewed. Also we need more sample from Indonesia for the better accuracy. 
Ah also we need to compare it with a real PM2.5 sensor.

You can find our model [Here](https://drive.google.com/drive/folders/1AZzoAmFqpJnRDUSKNBu14Y8MGBLLBcrL?usp=drive_link)