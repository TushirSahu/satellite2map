# satellite2map
![images](https://user-images.githubusercontent.com/96677478/222502920-9d9f6552-5e34-4141-a33a-90a334962247.jpeg)

## Why U-Net
![5705092b-50f5-4bfa-b4d7-6e43c85b343a](https://user-images.githubusercontent.com/96677478/222503013-3a59e1d6-f5a0-4b27-93b3-c275c3821d18.jpg)

Using a U-Net is a good choice because of the lack of training data, and it also seems to be the choice of most Kagglers that participated to this satellite imagery competition. This neural network architecture has revealed to be very good in this situation. U-Nets have an ability to learn in environments of low to medium quantities of training data, and the amount of training data available in this competition is considered low. Also, a U-Net can be adapted to recent research
## Dataset
### Context
Humans in the Loop is publishing an open access dataset annotated for a joint project with the Mohammed Bin Rashid Space Center in Dubai, the UAE.

### Content
The dataset consists of aerial imagery of Dubai obtained by MBRSC satellites and annotated with pixel-wise semantic segmentation in 6 classes. The total volume of the dataset is 72 images grouped into 6 larger tiles. The classes are:

Building: #3C1098
* Land (unpaved area): #8429F6
* Road: #6EC1E4
* Vegetation: #FEDD3A
* Water: #E2A929
* Unlabeled: #9B9B9B
