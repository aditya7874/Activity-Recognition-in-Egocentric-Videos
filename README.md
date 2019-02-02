# Activity-Recognition-in-Egocentric-Videos

K. Sai Suma, Gedela Aditya and Snehasis Mukherjee, Activity Recognition in Egocentric Videos Using Bag of Key Action Units, Proc. of ICVGIP 2018, IIIT Hyderabad, ACM, pp.- 9:1-9:9.

### Abstract:
• In this paper we present a novel methodology for recognizing human activity in Egocentric video based on the **Bag of Visual Features**. The proposed technique is based on the assumption that, only a portion of the whole video can be sufficient to identify an activity. 

• The proposed approach divides the video into smaller video segments called **Video Units**. Spatio-temporal features extracted from the units, are clustered to construct the dictionary of **Action Units (AU)**. 

• The AUs are ranked based upon their score of likeliness. The scores are obtained by constructing a weighted graph with the AUs as vertices and edge weights calculated based on the frequencies of occurrences of the AUs during the activity.

• The less significant AUs are pruned out from the dictionary, and the revised dictionary of key AUs are used for activity classification.

### Block Diagram of our Approach:
![Screenshot](Final.png)


### Steps Involved:
* sava_data.m - 
* STIP.m - 
* Create_Descriptor - 
* k_means.m - 
* Graph.m - 
* Histogram.m - 

### Experimentations:
1. STIP - Number of interest points in a frame.
2. k-means - The k value while applying k-means algorithm.
3. Graph - Number of nodes to be pruned out to form the reduced dictionary of AUs.

### FPPA Dataset:
Yipin Zhou and Tamara L. Berg. 2015. Temporal Perception and Prediction in Ego-Centric Video. In International Conference on Computer Vision. ICCV.
![Screenshot](Dataset.png)

