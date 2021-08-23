## 1 CIRCUMSTANCES OF CONCEPTION

* During Spring 2020, I visited my corner store in Chicago.  My plan was to scoop some essentials.  I soon found myself in a line that snaked up and down the aisles, and the line only continued to grow as new shoppers entered the store, many unmasked.  Aerosols and particles were plentiful.  After a few anxious minutes I left, immediately thinking there must be a better, clearer and more hospitable way for corner stores to do checkout.  

## 2 INTRODUCTION

* I cannot think of a recent period where so much has changed in the way people think about corner stores.  Tho these cornerstones are not deeply ingrained in our young American cities.  Acting almost like a lawyer, I am defending a worthy client who may be facing a quiet exit and doing so in a language many can understand.  My hope is to show how corner stores seed the kind of human associations essential to all democracies. Right now many corner stores are being stripped down to commercialism only.  
* My goal is to show how in the calm atmosphere of a well functioning corner store, people get to know one another and like each other and take care of each other. When people do this, they take an interest in each others mutual welfare; arguably a better and speedier form of welfare than it being doled out by government programs. What's more, entertainment begins to shine thru in the form of witty, silly and informative conversations among characters that adds a richness to all our lives. I believe the friendly rituals of many different kinds of regulars mingling is essential to healthy cities. 

## 3 MARKET CONTEXT

* The rise of city planning that discounts corner stores for urban renewal projects suggests we've lost probably half of corner stores that existed at mid-century. Thankfully for the corner stores that do remain advances in technology have given them far shinier tools.  Systems have gotten smaller, parallelized and now even run alongside smartphones. Progress has happened remarkably fast. And as folk knowledge of the corner store roots itself in machine learning, it could spark major improvements in how they perform checkout and inventory management. Ultimately this shift could better equip corner stores to survive and thrive in neighborhoods that desperately need them.

## 4 HOW WILL IT HAPPEN?

* Hyper-local by nature, corner stores are inherently loyal to their surrounding community. A good corner store's presence can't be underestimated.  To transform the corner store toolkit, and not just its IT department, we take mature open-source software and embed it in services everyone can trust. Our system assembles all the knowledge scattered throughout the corner store and translates it in ways that the system qnd shopkeeper can use to shape new and inherently helpful tools.

* What's unique about this application is that it accesses machine learning software both remotely and locally rather than installing them on big old actual computers.  Our end-to-end method adopts a sparse temporal sampling approach, with computation done on hand-sized computing devices equipped with their own cameras, so applications are highly automated, readily available and easy-to-use/modify. 

## 5 APPLICATIONS

* As sensors and processors get better, together they are able to process data themselves at the network edge on hand-sized processors, rather than solely in the cloud.  With that in mind, our applications soak up real-time video, recomplies them as custome data structures and translates them to lighten their computational costs. Ultimately, the goal is to multiply the efficiency of what humanity has done to keep track of inventory and conduct checkout for decades with reliable, small, thoughtfully designed technology.
* APPLICATION A -- Engage shopkeepers a bit differently by showing them their inventory flows in real-time, giving them "eyes in the back of their head" for the identity and location of their goods in real-time.  
* APPLICATION B -- People don't want to make payments, they want to do what a payment facilitates. Some want the option to grab goods on a pre-payment account and skip the line entirely. Some want their corner store to function like their own personal pantry where they come and go as they please not burdered by the the role of checkout. What's more, this application normalizes the idea of corner stores providing digital money for autonomous checkout directly to regulars by thru easy conversion of USD into digital corner store money with a simple swipe on a mobile app.  Pre-payment means transactions can be settled instantly on in-house digital ledgers, rather than the pipes of cards networks and banks. By pulling transactions out of the banking system we would also cut operating expenses for corner stores, which amount to 1-3% per transaction. 
* Tho these boosts in productivity will take time to work out.  New technology is an example of what economists would call "general-purpose technology", like electricity a century ago, it has the potential to boost productivity across many industries.  However, making the most of such tech takes time and experimentation. This accumulation of know-how means software designers like myself must collect "intangible capital" for reasons we don't yet understand. Until this intangible capital bears fruit, measured by surges in productivity, entrepreneurial types like myself will continue to prototype and test, over and over again and again.

## 6 METHODS

* Before even writing the first line of code I engaged in an ethnographic study of the corner store by working in one. By putting the guest and shopkeepers experience at the forefront, I could better design software principles from what I saw people doing. My belief is that the more you know about a product, the more likely you are to come with a big idea on selling it. This approach has made the job of developing a working feature list for uses of the imagined Applications A & B much easier.  My 1000+ hours of field work helped me better craft tools that understands what is important and what promises best resonate with shopkeepers and guests. 

* My mixed-methods research is rooted in:
  * on-the-ground fieldwork
  * creation of models
  * embedding models to target platform
  * empowering machine learning applications on hand-sized processors

## 7 WORKING FEATURES

  * Indexing Location of Goods on 4' x 12' Shelf 
    * (Category | Item | Unit | On Hand | Ordered | On Shelf | On Backstock 
  * Single Handed Pulls of Goods From Shelf
  * Double Handed Pulls of Goods From Shelf
  * Hand Offs of Goods Between People
  * Non Shelf Pulls of Goods
  * Tosses of Goods Between People
  * Misplaced Goods On Shelf
  * Final "Basket of Goods" Count Near Checkout
  * This dataset and its data pipelines are a growing list. This current dataset has 100 action-object classes, with 100 clips for each action and each clip running approx 10 seconds. In total this dataset has 10,000 videos. It should be noted that all clips collected have variable resolution and frame rates.

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

