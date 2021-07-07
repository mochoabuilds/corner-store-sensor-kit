## 1 WHY? AND HOW?

* New kinds of technologies are being used to monitor the essential retailer. As sensors and processors get better, they are increasingly able to process data themselves at the network edge on hand-sized processors, rather than centrally in the cloud.  By pushing local storage data we offer less points of entry for hackers while also simplifying computational loads and the need to transmit data unnecessarily.  Our computer vision application engages shopkeepers a bit differently by showing item flows in real-time, giving them "eyes in the back of their head" for the identity and location of their packaged goods.

* This research relies on a mix of methods such as:
  * data collection & on-the-ground fieldwork
  * creation of models
  * embedding models to target platform
  * empowering AI applications on edge devices 

## WHY? (FOR GUESTS & SHOPKEEPERS)

* As the lines between banks, tech and retail blur we must ask how technology is changing the retail checkout experience.  Guests may need to prepare for a long-term shift in how money and checkout works. _Our code runs on the idea that "people don't want to make payments, they want to do what a payment facilitates"._ Our proof of concept automates the dull and repetitive tasks of scanning goods by having sensors, a processor and many lines of code run autonomous checkout applications, future NLP based applications, etc.  We believe this approach gives shopkeepers some freedom from the register so they can focus on those things that create regulars.
* Our moonshot is to normalize the idea of retailers selling gift cards redeemable for autonomous checkout directly to guests. _Imagine walking into a retailer, "checking in" with your smartphone, browsing/shopping and then recieving an adjustable receipt upon walking out._ Pre-paying means transactions could be settled instantly on in-house digital ledgers, rather than the pipes of cards networks and banks. By pulling transactions out of the banking system we would also cut operating expenses for retailers, which amount to 1-3% per transaction.

## RESEARCH GOALS

* As with any AI / machine learning, the syllabus determines the outcome.  Our AI's syllabus is focused on the political value of time we may have not considered ourselves. 

## HOW? (PROBLEM SOLVING PROCESS)

##  IN-HOUSE REFERENCE LIBRARY

ACTIONS / OBJECTS TRACKED
  * Packaged Goods on 4' x 12' Shelf (Price | Sold By | Vendor | Product Wtg | Unit Cost | Quantity on Floor | Quantity Stored | Pars | Order Y/N)
  * Single Handed Pulls of Packaged Goods From Shelf
  * Double Handed Pulls of Packaged Goods From Shelf
  * Hand Offs of Packaged Goods Between People
  * Non Shelf Pulls of Packaged Goods
  * Tosses of Packaged Goods Between People
  * Misplaced Packaged Goods 
  * Final Packaged Goods Count Near Checkout
  * This dataset and its data pipelines are a growing list. This current dataset has 100 action-object classes, with 100 clips for each action and each clip running approx 10 seconds. In total this dataset has 10,000 videos. It should be noted that all clips collected have variable resolution and frame rates.

## "PRETRAINING"

* We use an offshoot of ImageNet model to pre-train our system. We are immensely grateful for ImageNet and the human labor it took to sort, label and prep the millions of images across thousands of categories. Pre-training helps us avoid representational bottlenecks, boost our activations per tile and better balance the width and depth of the network.  What's more this approach helps us better understand how to model spatio-temporal cues at different scales across multiple cameras.

## ADDRESSING DATA BIAS

## ANALYSIS, DESIGN & IMPLEMENTATION 

## TRAINING DETAILS

* Learning Rates 
* Additional Data Prep
* Testing

## EXPERIMENTS

* In this section we explore the accuracy and generalization of models on different benchmark data sets. 
* Accuracy = Repeatability + Calibration

## RESULTS

## MEASURING ACCURACY ACROSS BENCHMARK DATASETS

* UCF-101 DATASET - 13320 videos across 101 action classes
* Accuracy:
* HMDB-51 DATASET - 6766 videos across 51 action classes
* Accuracy:

## DISCUSSION

## APPENDIX A: "CORNER STORE v-1" EXPANDED

## ACKNOWLEDGEMENTS

* This work was supported by my immediate family, close friends, confidants, my neighborhood grocers/corner stores and the open source community. 

## SANDBOX

* Teaching computer vision systems NOT to use guest biometrics as a condition of accepting payment under the Song Beverley Act of 1971
* Determining the metrics that improve downstream performance
* Better understanding the front-back orientation of human limbs due to clothing, lighting, background, optical interference
* "What You Almost Bought" Merchant Facing Application
* Bridging the edge-cloud barrier to lower server costs?
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

