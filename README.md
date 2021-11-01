## 1 CIRCUMSTANCES OF CONCEPTION

* It was Spring 2020 and I was visiting my corner store.  The plan was to scoop some essentials.  Soon I found myself in a line snaking around the store. The walls were sweaty.  Masks also weren't a social mandate in Chicago just yet.  And it was raining aerosols and particles.  After a few anxious minutes in this I left, immediately thinking there must be a better, clearer and more hospitable way for corner stores to do checkout.  

## 2 TOWARDS BETTER TIMES AND PLACES

* I cannot think of a recent period where so much has changed in the way people think about corner stores.   Personally I feel they could have a deeper presence in our young American cities.  I don't want them facing a quiet exit.  So I must explain why in a language many can understand. My hope is to show how corner stores seed the kind of human associations essential to all democracies.
* 
* The goal of this project is to show in the calm atmosphere of a well functioning corner store, people get to take an interest in each others mutual welfare. What's more, corner store are entertainment.  Conversations with regulars begins to shine thru in the form of witty, silly and informative conversations among characters that adds a richness to all our lives. I believe these friendly rituals are essential.

## 3 MARKET CONTEXT (WHY THIS PROJECT)

* The rise of city planning that discounts corner stores for urban renewal projects suggests we've lost probably half of corner stores that existed at mid-century.  I can think of many sprinkled throughtout the side streets of Chicago's West Town neighbrhood. 
* My goal is deliver a small, parallelized processor that runs alongside smartphones. Progress has happened remarkably fast.  Personally I want to translate the folk knowledge of running a corner store roots into a neural net that assists the store's GM. It could spark major improvements in how a store performs inventory management, checkout, etc.  My hope is to beter equip corner stores for survival in these changing times.

## 4 HOW WILL IT HAPPEN? (HUMAN-COMPUTER INTERACTION)

* Hyper-local by nature, corner stores are inherently loyal to their surrounding community. A good corner store's presence can't be underestimated.  To transform the corner store toolkit, and not just its IT department, we take mature open-source software and embed it in a hand help sized durably dealed processor w/ sensors. 
* Our end-to-end method adopts a sparse temporal sampling approach, with computation done on hand-sized computing devices equipped with their own cameras, and we make applications highly automated, readily available and easy-to-use/modify. The computer assembles all the knowledge scattered throughout the corner store and translates it in ways that the computer & human use together to shape new and inherently helpful tools that multipy our efficiency.

## 5  TOOLS

* APPLICATION A -- Engage shopkeepers a bit differently by showing them their inventory flows on the floor/backstock in real-time, giving them "eyes in the back of their head" for the identity and location of all their goods in real-time.  
* APPLICATION B -- People don't want to make payments, they want to do what a payment facilitates. Some may want the option to grab goods on a pre-payment account and skip the line entirely. They may want their corner store to function like their own personal pantry where they come and go as they please.   
* Yet these boosts in productivity will take time to work out.  New technology is an example of what economists would call "general-purpose technology", like electricity a century ago, it has the potential to boost productivity across many industries.  However, making the most of such tech takes time and experimentation. This accumulation of know-how means software designers like myself must collect "intangible capital" for reasons we don't yet understand. Until this intangible capital bears fruit, measured by surges in productivity, entrepreneurial types like myself will continue to prototype and test, over and over again and again.

## 6 METHODS

* My mixed-methods research is rooted in:
  * on-the-ground fieldwork
  * creation of models
  * embedding models to target platform
  * empowering machine learning applications on hand-sized processors

* Before even writing the first line of code I engaged in an ethnographic study of the corner store amd currently working in one. By putting the guest and shopkeepers experience at the forefront, I believe I can better design software principles from what I see people doing. My belief is that the more you know about a product, the more likely you are to come with a big idea on selling it. This approach has made the job of developing a working feature list for uses of the imagined tool above much easier. 

## 7 WORKING FEATURE LIST

  * Indexing Location of Goods on 4' x 12' Shelf 
    * (Category | Item | Unit | On Hand | Ordered | On Shelf | On Backstock 
  * Single Handed Pulls of Goods From Shelf
  * Double Handed Pulls of Goods From Shelf
  * Hand Offs of Goods Between People
  * Non Shelf Pulls of Goods
  * Tosses of Goods Between People
  * Misplaced Goods On Shelf
  * Final "Basket of Goods" Count Near Checkout
 
## 8 "PRETRAINING"

* We use an offshoot of ImageNet model to pre-train our system. We are immensely grateful for ImageNet and the human labor it took to sort, label and prep the millions of images across thousands of categories. Pre-training helps us avoid representational bottlenecks, boost our activations per tile and better balance the width and depth of the network.  What's more this approach helps us better understand how to model spatio-temporal cues at different scales across multiple cameras.

## 9 ADDRESSING DATA BIAS

* Bias is inevitable when training machine learning models for human action-object detection in video streams. To counter this each respective corner store is made the center of the training dataset, to better debase the dominant groups claim as the norm for theories about how guests shop / leavier happier in corner stores. Our reality is political, but the machine learning developers perspective as the norm when training applications need not be. We believe this approach helps the models better "see" the sensitive interpretations of what humans feel at each respective corner store is important.

## 10 ANALYSIS, DESIGN & IMPLEMENTATION 

## 11 TRAINING DETAILS

* Learning Rates 
* Additional Data Prep
* Testing

## 12 EXPERIMENTS

* In this section we explore the accuracy/generalization of models on different benchmark data sets. We independently trained 7 versions of the same network, and they only differ in the random order in which they were training on Corner Store v-1 Data
* Accuracy = Repeatability + Calibration

## 13 RESULTS

## 14 MEASURING ACCURACY ACROSS BENCHMARK DATASETS

* UCF-101 DATASET - 13320 videos across 101 action classes
* Accuracy:
* HMDB-51 DATASET - 6766 videos across 51 action classes
* Accuracy:

## 15 DISCUSSION

## APPENDIX A: "CORNER STORE v-1" EXPANDED

## ACKNOWLEDGEMENTS

* This work was supported by my immediate family, close friends, confidants, my neighborhood grocers/corner stores and the open source community. 

## SANDBOX

* Teaching computer vision systems NOT to use guest bio-metrics as a condition of accepting payment under the Song Beverley Act of 1971
* Determining the metrics that improve downstream performance
* Better understanding the front-back orientation of human limbs due to clothing, lighting, background, optical interference
* "What You Almost Bought" Merchant Facing Application
* Bridging the edge-cloud barrier to lower server
 costs?
* Rewriting code and making arrays more ergonomic
* Lowering the costs of switching data across different corner stores
* Better understanding how social, economic and legal systems work together to achieve goals

## REFERENCES

* Writing Ethnographic Field Notes, 2nd Edition (2011)
* The Great Good Place by Roy Oldenburg (1989)
* "Covid-19 and Implications for Automation" (2020)
*
* Building Business Applications Using C++
* Knowledge Representation and Reasoning (2004)
* Learning OpenCV 3: Computer Vision in C++ with the OpenCV Library (2017)
*
* "Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset" (2018)
* "The Kinetics Human Action Video Dataset" (2017)
* "Two Stream Convolutional Networks for Action Recognition in Videos" 
* 
* "Towards Good Practices for Very Deep Two-Stream ConvNets" (2015)
* "FlowNet 2.0: Evolution of Optical Flow Estimation with Deep Networks" (2016)
* 
* "Going Deeper with Convolutions" (2014)
* "Rethinking the Inception Architecture for Computer Vision" (2015)

