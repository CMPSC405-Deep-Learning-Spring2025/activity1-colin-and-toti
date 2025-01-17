## Names: Colin and Toti

### Performance

Yes, the output makes sense. It was calculated using the number of hours before midnight you go to sleep, the number of hours after 7am you wake and the number of interruptions that wake you up during your sleep. The higher these numbers get, the less likely you are to go to class. Our bias increased the overall output by 1, which shows that students do want to go to class even if they are a bit tired. Ultimately, if the output is higher than 0 you will go to class. We adjusted weights so that some inputs were more significant than others. For example, the most important input is the time in which a person goes to bed, so this has the highest weight. The time in which the person wakes up is the least significant, so this has the lowest weight. This is because the time in which a person wakes up does not have much effect as long as they go to sleep at an appropriate time. We noticed that small changes in how we calculated input values had a large effect on output. For instance, the person’s bedtime is measured in hours before midnight in which they went to bed. At first, this number was 10:00, but then there were scenarios in our neural network where a student could get 8 hours of sleep and still not go to class. We felt that raising the number to midnight better captured college students’ habits and made more mathematical sense in our network too.


### Ethics

Some potential biases that we faced in this project was that we are more likely to go to class than the average student. Therefore we would have a higher bias value personally compared to our model. However, we did our best to stay objective and capture the student community as a whole. 

### Reflection

Setting up the inputs and creating our scenario was fairly easy. Getting the math to work properly and figuring out the proper weights for the inputs was a much more difficult task.
